# <img src="https://user-images.githubusercontent.com/70295997/216801040-8901bacf-53ba-4e75-b986-61ba518a1d2a.png" width=40> Android RunTime (ART)

__Dalvik__ was the original virtual machine (VM) used in Android to run applications written in Java. 
Dalvik was designed to be memory-efficient and optimized for mobile devices, with features like just-in-time (JIT) compilation and garbage collection. 
Dalvik was designed to be compact and efficient, allowing Android devices to run apps on limited resources.

In Android 4.4 (KitKat), the Dalvik VM was replaced with the __Android Runtime (ART)__, which provides improved performance and support for new features.

ART (Android RunTime) is the default runtime environment in Android devices, and is used to execute Android applications. ART works by compiling the application code into an optimized machine code format, rather than interpreting the code at runtime as was the case with the older Dalvik runtime. This allows for improved performance and battery life on Android devices.

Examples of how ART is used in Android include:

### <img src="https://user-images.githubusercontent.com/70295997/216800709-bde8dc15-0ea9-49ba-891f-872d2cafb502.png" width=40> Improved Application Compatibility
ART is designed to be more compatible with applications than its predecessor, Dalvik. This means that developers can create applications that run more smoothly and efficiently on Android devices, and that users are less likely to experience compatibility issues with their apps.

### <img src="https://user-images.githubusercontent.com/70295997/216800637-fc9323c3-18ac-4698-80a5-90c6a46cc67f.png" width=40> Improved Application Performance / Faster App Launch Times
ART uses ahead-of-time (AOT) compilation, which compiles the application code into machine code when the app is installed. This results in faster app launches and improved overall performance compared to the previous runtime environment, Dalvik.

### <img src="https://user-images.githubusercontent.com/70295997/216800759-4ccb0997-7ddd-4b7f-af54-9b2c788deed2.png" width=40> Improved Battery Life
ART performs runtime optimizations that can result in improved battery life, as the device does not need to constantly interpret the application code. Also, ART includes a garbage collector that optimizes memory usage and reduces power consumption, which results in improved battery life. This is especially important for mobile devices, where battery life is a critical factor.

### <img src="https://user-images.githubusercontent.com/70295997/216800844-fb4d7411-fdf1-4a13-be75-3040cb890151.png" width=40> Improved Garbage Collection
ART includes a more advanced garbage collection system, which helps to reduce memory usage and improve overall system performance.

### <img src="https://user-images.githubusercontent.com/70295997/216800890-ce4ff5fb-5a81-4c62-bb6a-a98b5b2a83e9.png" width=40> Smoother User Experience
ART is optimized for low-memory devices, which results in a smoother and more responsive user experience. This is especially important for devices with limited resources, as ART helps to ensure that applications run smoothly and efficiently.

<img src="https://user-images.githubusercontent.com/70295997/216801011-b6be3fe9-f2f7-4171-9282-4cb49e1a8722.png" width=40> Overall, ART is an important part of the Android operating system, as it provides the runtime environment for Android applications, and is responsible for improving performance, user experience, battery life, and application compatibility on Android devices.
