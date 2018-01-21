# The Observer Pattern

> defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically 

\- HFDP p.51 

This helps ensure loose coupling between objects, and 
only requires that each observer implement a common interface
so that can be called by the observer when it's state updates

There is a default implementation `java.util.Observable` and `java.util.Observer`.
The only thing that the Observerable needs to know about Observers is that they implement a certain interface!

## Problem statement from book 
To build a next-generation internet-based weather station. 
We are provided the [Weather Data](weatherobservable/WeatherData.java) API and will 
use this to build three different displays (current confitions, weather statistics and a simple forecast) 
as well as an API for other developers :smiley:


## Implementation 
There are three interfaces: 
[Subject](weather/Subject.java) (the Observable), 
[Observer](weather/Observer.java), and 
[Display Element](weatherobservable/DisplayElement.java)

The only Observable/Subject is the [Weather Data](weatherobservable/WeatherData.java) 
API we were provided. All of the other classes (
    [CurrentConditionsDisplay](weatherobservable/CurrentConditionsDisplay.java), 
    [StatisticsDisplay](weatherobservable/StatisticsDisplay.java),
    [ForecastDisplay](weatherobservable/ForecastDisplay.java)
)