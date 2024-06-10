<style>
    p{
        text-align:justify;
    }
</style>


# <a href="https://source.android.com/docs/core/architecture#:~:text=compatibility%20program.-,AOSP%20architecture,-The%20software%20stack" target="_blank">AOSP Architecture</a>


The Android Open Source Project (AOSP) architecture is a layered architecture that provides a complete implementation of the Android mobile platform. It's designed to be open and customizable, so developers and manufacturers can modify and distribute Android as they see fit. The AOSP architecture consists of several components, including:


<div style="text-align: center;">
    <img src="images/android-stack.svg" alt="Example Image" width="600" style="border: 2px solid black;">
</div>


<!-- <img src="" alt="Example Image" width="600" style="border: 2px solid black;" > -->


<!--![AOSP Architecture](images/android-stack.svg)-->


**Linux kernel** :The core layer of Android, providing essential features like memory management, device drivers, and process management. It acts as a bridge between the hardware and the upper layers of the Android Framework.


**Hardware Abstraction Layer (HAL)** : Abstracts hardware-specific functionalities into a standardized interface that the Android Framework can access.


**Libraries** : Provides the infrastructure for applications to run, including SSL, SQLite, and OpenGL.


**Application Framework** : Provides APIs that allow developers to create Android apps, and includes standard app components like activities, services, and content providers.