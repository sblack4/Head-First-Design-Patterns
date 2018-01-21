# Commands (and comments)
Commands to run java app examples from the book 
after ant build

## Compilation

### Ant build
Make sure you've installed [Apache Ant](http://ant.apache.org/)
then, from this directory run 
```sh 
ant -f build.xml
```

### Alternative, `javac` compilation
Alternatively you can compile the `.java` files this way...

1. `cd` into `Head-First-Design-Patterns/src` directory 
2. compile java files in directory with `javac headfirst/designpatterns/<dir_name>/*.java`
3. run file with `java headfirst.designpatterns.<dir_name>.<class_name>`

#### e.g. to run strategy/MiniDuckSimulator

1. `cd Head-First-Design-Patterns/src`
2. `javac headfirst/designpatterns/strategy/*.java`
3. `java headfirst.designpatterns.strategy.MiniDuckSimulator`


## Chapter 1 - Strategy Pattern

```java
java -cp ./classes headfirst.strategy.MiniDuckSimulator
java -cp ./classes headfirst.strategy.MiniDuckSimulator1
```

## Chapter 2 - Observer Pattern

```java
java -cp ./classes headfirst.observer.weather.WeatherStation
java -cp ./classes headfirst.observer.weather.WeatherStationHeatIndex
java -cp ./classes headfirst.observer.weatherobservable.WeatherStation
java -cp ./classes headfirst.observer.weatherobservable.WeatherStationHeatIndex
java -cp ./classes headfirst.observer.swing.SwingObserverExample
```

## Chapter 3 - Decorator Pattern

```java
java -cp ./classes headfirst.decorator.starbuzz.StarbuzzCoffee
```

For the InputTest example, make sure you have the file test.txt in 
the directory where you run headfirst.decorator.io.InputTest

```java
java -cp ./classes headfirst.decorator.io.InputTest
```

## Chapter 4 - Factory Patterns

### Simple Factory
```java
java -cp ./classes headfirst.factory.pizzas.PizzaTestDrive
```

### Factory Method
```java
java -cp ./classes headfirst.factory.pizzafm.PizzaTestDrive
```

### Abstract Factory
```java
java -cp ./classes headfirst.factory.pizzaaf.PizzaTestDrive
```

## Chapter 5 - Singleton Pattern

```java
java -cp ./classes headfirst.singleton.chocolate.ChocolateController
java -cp ./classes headfirst.singleton.stat.SingletonClient
java -cp ./classes headfirst.singleton.dcl.SingletonClient
java -cp ./classes headfirst.singleton.subclass.SingletonTestDrive
```

## Chapter 6 - Command Pattern

```java
java -cp ./classes headfirst.command.simpleremote.RemoteControlTest
java -cp ./classes headfirst.command.remote.RemoteLoader
java -cp ./classes headfirst.command.undo.RemoteLoader
java -cp ./classes headfirst.command.party.RemoteLoader
```

## Chapter 7 - Adapter and Facade Patterns

```java
java -cp ./classes headfirst.adapter.ducks.DuckTestDrive
java -cp ./classes headfirst.adapter.ducks.TurkeyTestDrive
java -cp ./classes headfirst.adapter.iterenum.EI one two three
java -cp ./classes headfirst.adapter.iterenum.IteratorEnumerationTestDrive one two three four five six
java -cp ./classes headfirst.adapter.iterenum.EnumerationIteratorTestDrive seven eight nine ten eleven twelve
java -cp ./classes headfirst.facade.hometheater.HomeTheaterTestDrive
```

## Chapter 8 - Template Method Pattern

```java
java -cp ./classes headfirst.templatemethod.simplebarista.Barista
java -cp ./classes headfirst.templatemethod.barista.BeverageTestDrive
java -cp ./classes headfirst.templatemethod.sort.DuckSortTestDrive
java -cp ./classes headfirst.templatemethod.frame.MyFrame
```

## Chapter 9 - Iterator and Composite Patterns

```java
java -cp ./classes headfirst.iterator.dinermerger.MenuTestDrive
java -cp ./classes headfirst.iterator.dinermergeri.MenuTestDrive
java -cp ./classes headfirst.iterator.dinermergercafe.MenuTestDrive
java -cp ./classes headfirst.composite.menu.MenuTestDrive
java -cp ./classes headfirst.composite.menuiterator.MenuTestDrive
```

## Chapter 10 - State Pattern

```java
java -cp ./classes headfirst.state.gumball.GumballMachineTestDrive
java -cp ./classes headfirst.state.gumballstate.GumballMachineTestDrive
java -cp ./classes headfirst.state.gumballstatewinner.GumballMachineTestDrive
```

## Chapter 11 - Proxy Pattern

```java
java -cp ./classes headfirst.proxy.javaproxy.MatchMakingTestDrive
java -cp ./classes headfirst.proxy.virtualproxy.ImageProxyTestDrive
```

to run the gumball proxy example:
 - run `headfirst.proxy.gumball.GumballMachineTestDrive <host> <# of gumballs>`
   on each machine
 - then run `headfirst.proxy.gumball.GumballMonitorTestDrive` to monitor them
 - you'll need to edit [GumballMonitorTestDrive](src/headfirst/designpatterns/proxy/gumball/GumBallMonitorTestDrive.java) to point to the correct machines
 - if you're running it all on the same machine, you can use `localhost` as the host

# Chapter 12 - Combining Patterns

Why a Duck?
```java
java -cp ./classes headfirst.combining.ducks.DuckSimulator
java -cp ./classes headfirst.combining.adapter.DuckSimulator
java -cp ./classes headfirst.combining.decorator.DuckSimulator
java -cp ./classes headfirst.combining.factory.DuckSimulator
java -cp ./classes headfirst.combining.composite.DuckSimulator
java -cp ./classes headfirst.combining.observer.DuckSimulator
```

## MVC

```java
java -cp ./classes headfirst.combined.djview.DJTestDrive
java -cp ./classes headfirst.combined.djview.HeartTestDrive
```

