In our project, we harness the power of Python to explore the intricate world of Simultaneous Localization and Mapping (SLAM), a pivotal concept in robotics. SLAM, an acronym for brevity, is the process of creating and updating maps using sensory data while carefully handling uncertainties. It forms the backbone of accurately determining the exact location of robotic systems. SLAM is especially vital when dealing with uncertain or vague sensory inputs and is the key to achieving complete autonomy in a wide array of robotic applications. These applications span from autonomous vehicles and unmanned aerial vehicles to autonomous underwater vehicles, rovers, and even domestic robots like cleaning bots.

To pinpoint a robot’s location accurately, we employ a variety of advanced techniques, including the Extended Kalman Filter, Maximum a Posteriori (MAP) estimation, and Bundle Adjustment (BA). Our project involves the careful collection of sensor data, with a focus on landmarks, and then interpreting their positions within a 2D space. This process is iterative and unfolds with each movement, gradually building a thorough understanding of the robot’s localization within its surroundings.

At the heart of our methodology is Graph SLAM, a technique that simplifies estimation by structuring probabilities as a set of constraints. Starting from an initial position, it incrementally refines calculations based on previous poses, ultimately determining the robot’s path within the environment. This approach allows us to handle large-scale environments and long-term mapping tasks more efficiently, making it a preferred choice for many real-world applications. Furthermore, Graph SLAM’s ability to incorporate loop closure information helps in correcting the robot’s trajectory over time, leading to more accurate maps. This makes it an invaluable tool in our quest to understand and implement SLAM.
