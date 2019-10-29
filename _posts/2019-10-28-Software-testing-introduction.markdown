---
layout: post
title: Software Testing Introduction
date: 2019-10-29 07:07:07 +0100
img: 8.jpg
tags: [Testing, UAT, SIT, UnitTest]
author: Ekuma Chidi
---

Testing, in general, refers to a deliberate action to find out how well something works.

![](https://miro.medium.com/max/1460/0*4xbcV_V3EVd-MT2B)

**Image Credits:** ribkhan / Getty Images (Image has been modified)

I hear arguments amongst IT professionals about the different levels of testing; mostly around unit tests and system tests. The most recent one was between a Business Analyst (BA) and a Developer(Dev). The BA was of the opinion that unit tests are all the tests done by the Dev; any test that is done by the developer as she/he is building the application is “unit-test” and then when he’s done the Quality Assurance (QA) professional carries out a System Integration Test (SIT).

Agreeably there are different levels of testing:

1.  Unit test
2.  Integration test
3.  System test
4.  Acceptance test

**What is a unit test?**

Unit tests are carried out to validate that every unit of the software performs as designed; this testing is done on individual units/components.

> Hmm…what then is a “unit”?

A unit is the **smallest testable part** of a given software. A general misconception is to treat a module as a unit. This is very wrong. In Object-Oriented Programming (OOP), a unit would be a method which may belong to a class.

If we agree on the above, then unit tests are done by developers, however, it may also be done by an independent tester.

**Why write unit tests?**

1.  Good unit tests make code maintenance easier because the tests can be run each time there’s a change so you can catch and fix bugs that may be introduced by the changes.
2.  Ensures cleaner code; unit testing makes developers write modular reusable codes.
3.  Because defects are caught much earlier, it is less expensive and faster to resolve them.

> Even though this generally increases dev time, the benefits make it worthwhile.

**What then is an integration test?**

Integration tests combine multiple units and test them as a group to ensure that these components interact seamlessly.

This test can be conducted by developers or independent testers. In most organizations the big bang approach is used; the testing team receives the whole application in a bundle to test at one go.

**How about System Test?**

At this level, the complete and fully integrated software is tested to ensure that the specified requirements are met. This level of the test is usually carried out by an independent tester.

**OK, so what then is the Acceptance Test?**

During the acceptance test, the software is tested against user needs, requirements and business processes to confirm that the system meets the acceptance criteria. At this level, the testing doesn’t follow a script. It is done after the system test is completed, and tends to be ad-hoc. This test is usually carried out by product managers/ end users.