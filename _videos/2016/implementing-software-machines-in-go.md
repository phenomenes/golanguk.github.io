---
title: "Implementing Software Machines in Go (and C)"
metatitle: "Implementing Software Machines in Go"
speaker: Eleanor McHugh
video-id: b3ji5tdZUfY
length: "0:43:57"
---
I’ve been interested in the design and implementation of virtual machines since encountering the source code for a simple Forth interpreter written in Basic when I was 15. It was a fascinating, inscrutable piece of magic which played a key role in my becoming a professional programmer.<br><br>Most of us who've played games or worked in any one of a number of popular programming languages will have used virtual machines but unless we've taken a course in programming language design we probably have only a loose idea of what these are and how they work.<br><br>In this workshop we'll look at the various parts necessary to model a computer-like machine in code, borrowing ideas as we go from real-world hardware design. We'll use a mixture of C and Go as our modelling languages: C is the lingua franca of the VM world whilst Go has excellent tooling and concurrency.<br><br>We'll also examine some of the benefits of phrasing software development problems in mechanistic terms. These include ease of composition, automation, security, testing, repeatability and reasoning about performance.<br><br>You'll need a laptop with Go and a recent version of Clang or GCC installed and a basic grasp of Go.