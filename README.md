Semi-Rigid PC Beam-Column Node Hysteresis Preview Platform


This project introduces a Unity®-based preview platform for simulating and analyzing the hysteretic behavior of semi-rigid precast concrete (PC) beam-column nodes. It integrates multi-type deep learning algorithms with finite element simulation (ABAQUS®) to support refined node design and inverse analysis.

🔧 Key Features


Integrated Simulation Workflow: Combines design schemes, ABAQUS simulations, and deep learning models within a unified Unity environment.


Interactive Model Handling: Supports interactive extraction and parsing of .obj models via custom scripts (objSave.py, objLoader.cs).


Deep Learning Integration: Embeds deep learning models into the platform menu for user-friendly operation (AIToolsMenu.cs).


Multi-Source Data Synchronization: Implements efficient data transmission and time synchronization strategies (DataManager.cs, TimeSyncController.cs).


Dynamic Visualization: Provides multi-angle, multi-resolution visualization of time-varying damage processes (ModelView.cs, CameraCapture.cs).


Result Interpretation: Includes modules for semantic segmentation, image-point cloud registration, and interactive damage prediction charts (SegmentationView.cs, RegistrationView.cs, DamageXCharts.cs).
