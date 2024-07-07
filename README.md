# Violation-Detection-GPS

## Project Description

This is a GPS tracking system with new features such as:

- Geofencing
- Speed Limitation

The tech stack for the project consists of two main components:

- **Software**
- **Hardware**

The **Software** stack is created using ReactJS for the front-end, Flask framework for the back-end with JWT for authentication, and PostgreSQL for the database.

The **Hardware** architecture consists of an ESP32 microcontroller, a SIM700C SIM module, and a NEO-6M GPS module.

### Hardware Connection

![Hardware Architecture](/imgs/hardware_architicture.jpeg)

To transform this app into a microservices architecture, Docker was used to containerize the back-end services, the database, and the front-end.

Finally, the app was deployed on AWS using an EC2 instance with an Elastic IP address to connect the React app with the Flask APIs. I used an Application Load Balancer to distribute traffic across multiple EC2 instances to ensure high availability and scalability in case of server failures.

### Architecture of the Final Result

![Architecture](/imgs/architicture.jpeg)

### Steps to Run the React App Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/omaraliii1/Violation-Detection-GPS.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Violation-Detection-GPS/front
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

   ## Documentation will be provided in the files

# GPS-Violation-Detection
