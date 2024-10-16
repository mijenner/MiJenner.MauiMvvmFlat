## MiJenner.MauiMvvmFlat 
This is a template for my high school students for doing .NET MAUI apps with a MVVMS architecture. Idea is that they use it for
(a) learning the structure of MVVM architecture, (b) learn how to set up "things" in .NET MAUI, (c) use it as a basis for their own applications. 

# Features 
It doesn't use folders for the MVVMS architecture. Instead model, view and viewmodels are all located in the root. Idea is to keep the first attempts simple and avoid the hassle of many possible namespace issues in xaml code. 

# Package dependencies 
It uses Nuget packages: CommunityToolkit.Mvvm (https://learn.microsoft.com/en-us/dotnet/communitytoolkit/mvvm/) and CommunityToolkit.Maui (https://github.com/CommunityToolkit/Maui) enabling less boilerplate code to be written. 

It uses MiJenner.ServicesMAUI Nuget package, source code here: https://github.com/mijenner/MiJenner.ServicesMAUI for easy file-system access 
and storage of user settings. This is highly inspired by Mr Daniel Hindrikes. 

It uses MiJenner.ServicesGeneric Nuget package, source code here: https://github.com/mijenner/MiJenner.ServicesGeneric for an in-memory memory storage. 
