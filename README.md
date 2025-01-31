# 013 Service Lifetimes

## Lecture

[![# Service Lifetimes](https://img.youtube.com/vi/5UnRKwybV1c/0.jpg)](https://youtu.be/5UnRKwybV1c)

## Instructions

In `HomeEnergyApi/Program.cs`
- Replace the line `builder.Services.AddSingleton<IControllerFactory, ApplicationFactory>()` with `builder.Services.AddSingleton<IRepository<int, Home>, HomeRepository>();`.

Delete the file `HomeEnergyApi/ApplicationFactory.cs`

## Additonal Information
- So far in this course, `using` statements in `HomeEnergyApi` have been pre-provided for you, remember in the future you may need to add these yourself depending on the dependencies your projects have.

## Building toward CSTA Standards:

- Decompose problems into smaller components through systematic analysis, using constructs such as procedures, modules, and/or objects. (3A-AP-17) https://www.csteachers.org/page/standards
- Construct solutions to problems using student-created components, such as procedures, modules and/or objects. (3B-AP-14) https://www.csteachers.org/page/standards
- Compare levels of abstraction and interactions between application software, system software, and hardware layers. (3A-CS-02) https://www.csteachers.org/page/standards
- Demonstrate code reuse by creating programming solutions using libraries and APIs. (3B-AP-16) https://www.csteachers.org/page/standards

## Resources

- https://learn.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-8.0#service-lifetimes
- https://en.wikipedia.org/wiki/Inversion_of_control

Copyright &copy; 2025 Knight Moves. All Rights Reserved.
