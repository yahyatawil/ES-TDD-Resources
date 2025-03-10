# ES-TDD-Resources
A list of resources to learn about Test Driver Development in Embedded Systems🤖📟.  

# Table of Contents
- 📺[Videos](##videos)
- 📝[Tutorials&Articles](##tutorialsarticles)
- 📚[Books](##books)
- 📊[Researches](##researches)
- 💬[Community discussions](##community-discussions)


## Videos

**Zephyr Application Development Using TDD: Getting Started** – Luis Ubieda, Croxel, Inc. - 

🔗 https://www.zephyrproject.org/expert-insights-into-test-driven-development-pytest-integration-emulators-and-unit-testing/

These are a few videos from the Zephyr Developer Summit that answer questions about applying TDD and unit testing in RTOS and complex systems like Zephyr.


**TDD for Microcontrollers**- Daniel Penning - Meeting C++ 2023 - 

🔗 https://www.youtube.com/watch?v=EvvJE0AYeZw

The presenter in this video briefly explains the TDD concept using an example of calculating a CRC function. He discusses the differences between off-target and on-target unit testing and how they relate to TDD principles. Additionally, he introduces a solution to enhance the TDD process by using a hardware platform that enables “pin-based” testing, ensuring that even signals from MCU pins behave as expected. He also demonstrates how tests are written in a style similar to Behavior-Driven Development (BDD) but using Robot Framework.

**emBO++ 22: "Unembedding" embedded systems with TDD: benefits of going beyond the make-it-work phase** - 

🔗 https://www.youtube.com/watch?v=gT4bg0jYo58

This presentation discusses the impact of TDD on the internal quality of embedded software. The speaker explores mutation testing, a technique used to evaluate the quality of test cases. It works by intentionally introducing small changes in the code and checking whether the unit tests detect them. If a test catches the change, it is considered strong; otherwise, it is weak.

**Test-Driven Development of C++ Embedded and System-Level Software - Vladimir Vishnevskii - ACCU 2023** - 

🔗 https://www.youtube.com/watch?v=PYc2KuFce7o

This advanced talk covers TDD topics such as runtime polymorphism in unit testing, link-time substitution, polymorphic function wrappers, and compile-time polymorphism. The presentation includes a demo project that reads switch status and sends it to an HMI.

## Tutorials&Articles

**Test-Driven Development: The bug killer** - 

🔗 https://embeddedhackster.org/emb-sw/tdd 

This tutorial is highly informative as it demonstrates how to build a circular buffer using dual-target TDD step by step. It uses Unity framework. It also showcases on-target TDD by running Unity directly on the MCU.

**Unit-testing (embedded) C applications with Ceedling** - 

🔗 https://dmitryfrank.com/articles/unit_testing_embedded_c_applications

This is a very detailed tutorial that shows how the author developed firmware for a battery charger indicator. The project included various modules, such as ADC and Display. The author used Unity, CMock, and Ceedling.

**Benefits of Embedded TDD** - 

🔗 https://levelup.gitconnected.com/benefits-of-embedded-tdd-74c345c75a46

This blog discusses writing a library for a WiFi module to send commands through the UART interface.

**Mocking Embedded Hardware Interfaces with Ceedling and CMock** - 

🔗 http://www.electronvector.com/blog/mocking-embedded-hardware-interfaces-with-ceedling-and-cmock

This tutorial provides demo code for building temperature reading via I2C using TDD. The author used Ceedling.

**Unit Testing For Embedded Software Development** - 

🔗 https://dojofive.com/blog/unit-testing-for-embedded-software-development

This article explains TDD and the foundational concepts needed to understand it.


**Embedded C/C++ Unit Testing Basics** - 

🔗 https://interrupt.memfault.com/blog/unit-testing-basics

**Embedded C/C++ Unit Testing with Mocks** - 

🔗 https://interrupt.memfault.com/blog/unit-test-mocking

These two tutorials are excellent for building a foundation in unit testing for embedded systems. Memfault is well-known for its specialization in hardware testing, making the tutorials both informative and practical.

## Books

* **Test-Driven Development for Embedded C** by James Grenning: It is the only book specifically focused on applying TDD in embedded systems. Its author is regarded as a pioneer in this field, making the book a key reference on the subject.

* **Test-Driven Development as a Reliable Embedded Software Engineering Practice**: It is a chapter in the book "Embedded and Real-Time System Development: A Software Engineering Perspective" that provides a detailed explanation of TDD. It discusses the constraints of using TDD in embedded systems and offers suggestions for improvements.


## Researches 

**Test-Driven Development and Embedded Systems: An Exploratory Investigation** - 

🔗 https://ieeexplore.ieee.org/document/10371442

This research examines the impact of TDD on both embedded software quality and developer productivity. The study includes a use case where nine developers use TDD for the first time, comparing quality and productivity with and without TDD.

**Evaluation of Test-Driven Approaches for Embedded Software Development** - 

🔗 https://aaltodoc.aalto.fi/items/26c04f22-146a-418f-89fd-5318895aad98

This thesis explores Test-Driven Development (TDD) in detail. As is common with academic theses, it includes a comprehensive introduction to TDD and unit testing, covering advanced topics such as test double replacement techniques as background. The author applies TDD to a real project—a motor controller—demonstrating how dependencies from the STM32 SDK can be replaced to enable TDD development using various replacement techniques.



## Community discussions

https://www.reddit.com/r/embedded/comments/10vj7oy/howdo_you_guys_implement_tdd_test_driven/

https://www.reddit.com/r/embedded/comments/rrr09k/how_does_your_team_do_tdd_in_embedded_systems/

https://www.reddit.com/r/embedded/comments/1br32pg/how_relevant_is_tdd_to_your_firmware_systems/

https://www.reddit.com/r/embedded/comments/tfbjf2/does_your_company_utilize_testdriven_development 


