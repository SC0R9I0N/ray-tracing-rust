# ray-tracing-rust
Ray Tracing module in Rust, inspired by "Coding Ray Tracing in C" by HircschDaniel on YouTube

You can find the inspiration for this project [here](https://youtu.be/2BLRLuczykM?si=MF_Luvzsc7d3DdTn).

Similar to the inspiration, it will serve as an independent, standalone application in which ray tracing is simulated where there is a point of light and a sphere that blocks light.

To expand upon the inspiration, the application will accomplish 2 additional things:
1. it will have more complex settings so that you can simulate more complex ray tracing rather than just a sphere blocking light
   - it will have the ability to add additional objects to the window of different sizes and shapes
   - the "material" of the borders and objects will be able to be changed individually at very granular levels
   - effectively, these changes will allow for the ray tracing to simulate more effectively natural light by allowing multiple complex objects that can either mostly absorb light or mostly reflect light.
   - these new features will contain their own design UI that is seemlessly integrated into the base application
2. the UI of the application will be overhauled
   - this application is intended to not only be for myself, but also for others to test my ray tracing to potentially use in their own projects.
   - the new UI will also allow users to make minor adjustments in the ray tracing so that they can tailor it to their own personal needs

In addition to the standalone application, the code for just the actual ray tracing will be available. My base (no user-defined tweaks) version will be available in this repository for download, but there will be an option to export the user-tweaked version from the application so it saves the modified version of the ray tracing without the application-defining code. This addition is to allow for people to save their ray tracing configuration for projects, as well as to include the base version in a future game project I have in mind.
