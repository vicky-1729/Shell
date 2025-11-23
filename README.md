
# 🐚 Shell Scripting Projects

A comprehensive collection of Shell scripting projects and practice exercises showcasing automation and scripting capabilities.

## 📂 Repository Structure

This repository is organized into the following sections:

### [Shell Practice Scripts](./shell-practice/)

A collection of basic to intermediate shell scripts used for learning and practicing shell scripting concepts:

- **Variables and Echo Commands**: [demo-00.sh](./shell-practice/demo-00.sh), [demo-01.sh](./shell-practice/demo-01.sh), [demo-02.sh](./shell-practice/demo-02.sh)
- **Command Line Arguments**: [demo-03.sh](./shell-practice/demo-03.sh), [demo-04.sh](./shell-practice/demo-04.sh)
- **Conditional Statements**: [demo-05.sh](./shell-practice/demo-05.sh), [demo-06.sh](./shell-practice/demo-06.sh)
- **Loops and Iterators**: [demo-07.sh](./shell-practice/demo-07.sh), [demo-08.sh](./shell-practice/demo-08.sh)
- **Functions and Procedures**: [demo-09.sh](./shell-practice/demo-09.sh), [demo-10.sh](./shell-practice/demo-10.sh)
- **Process Management**: [demo-11.sh](./shell-practice/demo-11.sh), [demo-12.sh](./shell-practice/demo-12.sh)

### [RoboShop Shell Automation V1](./roboshop-shell-automation-01/)

A shell script-based automation project for deploying the RoboShop e-commerce application:

- **Frontend Service**: [frontend.sh](./roboshop-shell-automation-01/frontend.sh) - Configures and deploys the web UI
- **Catalogue Service**: [catalogue.sh](./roboshop-shell-automation-01/catalogue.sh) - Manages product listings
- **User Service**: [user.sh](./roboshop-shell-automation-01/user.sh) - Handles user management and authentication
- **Cart Service**: [cart.sh](./roboshop-shell-automation-01/cart.sh) - Manages shopping cart operations
- **Shipping Service**: [shipping.sh](./roboshop-shell-automation-01/shipping.sh) - Handles shipping logistics
- **Payment Service**: [payment.sh](./roboshop-shell-automation-01/payment.sh) - Processes payment transactions
- **Database Components**:
  - [mongodb.sh](./roboshop-shell-automation-01/mongodb.sh) - NoSQL database for catalogue and users
  - [redis.sh](./roboshop-shell-automation-01/redis.sh) - In-memory cache for cart data
  - [mysql.sh](./roboshop-shell-automation-01/mysql.sh) - Relational database for shipping
- **Message Queue**:
  - [rabbitMQ.sh](./roboshop-shell-automation-01/rabbitMQ.sh) - Message broker for asynchronous processing
- **Dispatch Service**: [dispatch.sh](./roboshop-shell-automation-01/dispatch.sh) - Handles order dispatching
- **Full Deployment**: [roboshop_server.sh](./roboshop-shell-automation-01/roboshop_server.sh) - Orchestrates complete deployment

### [RoboShop Shell Automation V2](./roboshop-shell-automation-02/)

An enhanced version of the RoboShop automation with improved structure and reusable components:

- **Common Functions**: [common_script.sh](./roboshop-shell-automation-02/common_script.sh) - Shared functions and utilities
- **Service Scripts**: Same component structure as V1, but with optimized code
- **Configuration Templates**: [repo_config/](./roboshop-shell-automation-02/repo_config/) - Contains service configuration templates
- **Service Definitions**: [service/](./roboshop-shell-automation-02/service/) - Systemd service file templates

## 🚀 Getting Started

### Prerequisites

- Linux-based operating system (Ubuntu, CentOS, etc.)
- Bash shell (version 4.0 or higher)
- Root/sudo access for service installation scripts

### Running the Practice Scripts

```bash
# Navigate to shell-practice directory
cd shell-practice

# Make scripts executable
chmod +x demo-*.sh

# Run a specific script
./demo-01.sh
```

### Deploying RoboShop Application

```bash
# Navigate to roboshop-shell-automation-02 directory
cd roboshop-shell-automation-02

# Make scripts executable
chmod +x *.sh

# Run the full deployment
sudo ./roboshop_server.sh

# Or deploy individual components
sudo ./frontend.sh
sudo ./catalogue.sh
# etc.
```

## 📝 Key Concepts Covered

- Variable declaration and usage
- Command-line argument processing
- Conditional logic (if-else, case statements)
- Looping constructs (for, while, until)
- Function definitions and usage
- File operations
- Process management
- Error handling and logging
- Service configuration and management
- System administration tasks automation

## 🔍 Project Highlights

- **Modular Design**: Each script focuses on a specific service or concept
- **Reusable Components**: Common functions extracted to avoid repetition
- **Error Handling**: Robust error checking and reporting
- **Logging**: Detailed logs for troubleshooting
- **Idempotent Execution**: Scripts can be run multiple times safely
- **Documentation**: Well-commented code for learning purposes

## 📅 Last Updated

September 7, 2025
