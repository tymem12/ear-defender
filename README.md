# EarDefender
main repository 

## Setup Instructions

To set up and launch the Detector Module, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/tymem12/ear-defender.git
   ```
2. **Initialize and Update Submodules**:

   After cloning the repository, update submodules to ensure all necessary components are available.
   ```bash
   git submodule update --init --recursive
   ```

4. **Initialize and Update Submodules**:

   Initialization of maven:
   ```bash
   cd connector
   mvn clean package
   cd ../
   ```

6. **Build and Run the Docker Container**:
   Use Docker Compose to build and start the container:
   ```bash
   docker compose up
   ```
