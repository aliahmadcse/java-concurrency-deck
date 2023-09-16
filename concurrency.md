---
marp: true
theme: default
_class: lead
author: Ali Ahmad
paginate: true
backgroundColor: #ffffff
# backgroundImage: url('https://marp.app/assets/hero-background.svg')
backgroundImage: url('./background.jpg')

---
# **Java Concurrency**

---

## **Agenda**

* Threads
* Process
* Using threads
* Daemon threads
* Life cycle and threads states
* Sleeping, joining and interrupting threads

---
## **Agenda**

* Race conditions
* Synchronization
* Monitors and structured locking
* The volatile keyword
* Thread local

---

## **Agenda**

* Advanced concurrency APIs
* Unstructured locks
* Executor service
* Thread pool types
* Callables and Future
* Semaphores
* Fork Join framework
* *Virtual Thread*

---
## **Thread**

* > A thread is a single sequential flow of control within a program.

---
## **Thread**

* Single sequential flow of control
* Allow the program to split into simuntanously running task
* As a metaphor - A worker who is building a wall

---
# **Process**

## Execution -> process

---

## **Process**
* Load program to memory
* Allocate the resources
* Execute the program
---

## **Process**

* > A process is a manifestation of a run state of an application.

---
## **Process**

* Binary instructions loaded into memory
* Get access to resources like memory
* Resource is protected from other processes

---

## **Process vs Threads**

* A process can be single threaded or multi threaded
* A process can spawn multiple threads
* Unlike process, threads in a process can share the same memory and resources


