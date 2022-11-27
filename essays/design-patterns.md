---
layout: essay
type: essay
title: Patterns Shmatterns
# All dates must be YYYY-MM-DD format!!
date: 2022-11-26
published: true
labels:
  - Design
  - Frameworks
---
*Why it matters*
### Design Project Mayhem
<div>
  <img length="125px" class="rounded float-start pe-4" src="https://media.giphy.com/media/l3q2Wl7Wpz09Z5hfi/giphy.gif">
  Despite experiencing numerous assignment, programs, projects, and essays during my time in university, it never fails to surprise me how I can make completing my work more difficult than it should be. I sometimes have a tendency to start writing a paper from top to bottom, even if there are sections below I can complete quicker or write computer programs without thinking of an algorithm first. These are all examples of me failing to utilize study and work patterns that have kept me successful in turning in quality work. Things such as getting enough rest, taking proper notes, eating a healthy diet and exercising also play an important role in my efficiency. Similarly, in the world of computers, we can utilize tried and proven design patterns that prevent us from "Reinventing the wheel" everytime we work on a problem. In the next few sections we will discuss some of these design patterns in detail.
</div>
<br>

### Common Design Patterns
  The term Design Patterns was defined in 1977 by an architect of the name Christopher Alexander in his book, <a href="https://en.wikipedia.org/wiki/A_Pattern_Language">A Pattern Language<a/>. He described it *as a problem that occurs over and over again in our environment and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice.* This definition was profound in that despite having a new problem, though not necessarily identical to an old one you've encountered, the older solutions can be used to as a template or guide to how tackling the problem can be structured. A simple example would be the type of roofs built in an environment such as Alaska. Although weather can vary geographically, common sense and experience would tell us that flat roofs would not do well in a snowy environment where pointy roofs are much more reasonable against the weather.

  In terms of software design, A group of software developers, inspired by Christopher Alexander's views on design patterns, published a <a href="">book</a> on software development patterns. They would later be famously dubbed as the *Gang of Four*. The 23 patterns the authors/developers identified could be broken into three types: Creational, Structural, and Behavioral. Like the the roofs in Alaska, we can identify patterns in our programming objective that can help us find the right solution. 
  <ol>  
    <img width="200px" class="img-fluid" src="https://media.giphy.com/media/133c9SJrrC2bni/giphy.gif" style="float:right;margin-left:2px;">
    <li>
      <h5>Creational</h5>
      <p>
        Provides different ways to create an object.
      </p>
    </li>
    <li>
      <h5>Structural</h5>
      <p>
        Provides relationships between objects.
      </p>
    </li>
    <li>
      <h5>Behavioral</h5>
      <p>
        Provides how objects interact or communicate with one another.
      </p>
    </li>
  </ol>
<br>
<p>Above are the types of design patterns for object oriented programming and their definition. Below is a table of the Patterns defined by the Gang of Four and summarized in an <a href="https://blog.devgenius.io/gang-of-four-design-patterns-8c85a80eac0a">blog post</a> by Ela Singh.</p>
<br/>
<table>
 <tr>
    <th>Creational Design Pattern</th>
    <th>Description</th>
 </tr>
 <tr>
    <td>Abstract Factory</td>
    <td>Allows the creation of objects without specifying their concrete type.</td>
 </tr>
 <tr>
    <td>Builder</td>
    <td>Uses to create complex objects.</td>
 </tr>
 <tr>
    <td>Factory Method</td>
    <td>Creates objects without specifying the exact class to create.</td>
 </tr>
 <tr>
    <td>Prototype</td>
    <td>Creates a new object from an existing object.</td>
 </tr>
 <tr>
    <td>Singleton</td>
    <td>Ensures only one instance of an object is created</td>
 </tr>
</table>
<br/>
<table>
    <tr>
        <th>Structural</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Adapter</td>
        <td>Allows for two incompatible classes to work together by wrapping an interface around one of the existing classes.</td>
    </tr>
    <tr>
        <td>Bridge</td>
        <td>Decouples an abstraction so two classes can vary independently.</td>
    </tr>
    <tr>
        <td>Composite</td>
        <td>Takes a group of objects into a single object.</td>
    </tr>
    <tr>
        <td>Decorator</td>
        <td>Allows for an object’s behavior to be extended dynamically at run time.</td>
    </tr>
    <tr>
        <td>Facade</td>
        <td>Provides a simple interface to a more complex underlying object.</td>
    </tr>
    <tr>
        <td>Flyweight</td>
        <td>Reduces the cost of complex object models.</td>
    </tr>
    <tr>
        <td>Proxy</td>
        <td>Provides a placeholder interface to an underlying object to control access, reduce cost, or reduce complexity.</td>
    </tr>
</table>
<br/>
<table>
    <tr>
        <th>Behavioral</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Interpreter</td>
        <td>Implements a specialized language.</td>
    </tr>
    <tr>
        <td>Chain of Responsibility</td>
        <td>Delegates commands to a chain of processing objects.</td>
    </tr>
    <tr>
        <td>Command</td>
        <td>Creates objects which encapsulate actions and parameters.</td>
    </tr>
    <tr>
        <td>Iterator</td>
        <td>Accesses the elements of an object sequentially without exposing its underlying representation.</td>
    </tr>
    <tr>
        <td>Mediator</td>
        <td>Allows loose coupling between classes by being the only class that has detailed knowledge of their methods</td>
    </tr>
    <tr>
        <td>Memento</td>
        <td>Provides the ability to restore an object to its previous state.</td>
    </tr>
    <tr>
        <td>Observer</td>
        <td>Is a publish/subscribe pattern which allows a number of observer objects to see an event.</td>
    </tr>
    <tr>
        <td>State</td>
        <td>Allows an object to alter its behavior when its internal state changes.</td>
    </tr>
    <tr>
        <td>Strategy</td>
        <td>Allows one of a family of algorithms to be selected on-the-fly at run-time.</td>
    </tr>
    <tr>
        <td>Template Method</td>
        <td>Defines the skeleton of an algorithm as an abstract class, allowing its sub-classes to provide concrete behavior.</td>
    </tr>
    <tr>
        <td>Visitor</td>
        <td>Separates an algorithm from an object structure by moving the hierarchy of methods into one object.</td>
    </tr>
</table>
<br/>

### Putting Patterns to Practice
From this list of patterns...




