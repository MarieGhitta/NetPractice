*This project has been created as part of the 42 curriculum by mghitta*.

# NetPractice

## Description

NetPractice is a practical networking project designed to introduce the basics of computer networking.

The goal is to configure small simulated networks so that all devices can communicate correctly. The exercises focus on TCP/IP addressing and require understanding how IP addresses, subnet masks, default gateways, routers, and switches interact within a network.

The project consists of **10 levels**. Each level presents a non-functioning network configuration with objectives to achieve. The configuration must be adjusted until the network works correctly.

The networks used in this project are simulated and do not represent real networks.

## Instructions

### Launching the training interface

The NetPractice interface requires a local web server.

1. Download and extract the NetPractice files provided with the project.
2. Run the `run.sh` script from the extracted directory:

```bash
./run.sh
```

3. The script starts a local web server and opens the NetPractice interface in a web browser.

If `run.sh` does not work correctly, the server can be started manually:

```bash
python3 -m http.server 49242
```

Then open the following address in your browser:

```text
http://localhost:49242
```

The port number can be changed if necessary.

### Completing the levels

The training interface contains **10 levels**.

For each level:

1. Read the objective displayed at the top of the page.
2. Modify the available configuration fields to make the network function correctly.
3. Click **Check again** to verify the configuration.
4. Use the logs displayed at the bottom of the page to understand configuration errors.
5. Once the level is successfully completed, click **Get my config** to export the configuration.
6. Save the exported configuration file in the root of this repository.
7. Proceed to the next level.

It is important to enter your **42 login** in the NetPractice interface before exporting the configurations.

### Submission

The repository must contain **10 exported configuration files, one for each level**, placed at the **root of the repository**.

Only the contents of the Git repository are evaluated during the defense, so make sure all 10 configuration files have been exported and committed.

During the defense, three random levels must be successfully completed within a limited amount of time. External tools are not allowed during the evaluation. A simple calculator such as `bc` is tolerated.

## Resources

The main topics studied during this project are:

- TCP/IP addressing
- IP addresses
- Subnet masks and subnetting
- Network and host addresses
- Default gateways
- Routers
- Switches
- Communication between devices on different networks
- OSI model and network layers

### TCP/IP addressing

- https://www.fortinet.com/fr/resources/cyberglossary/tcp-ip

### Subnet masks

- https://www.lenovo.com/be/fr/glossary/netmask/

### Default gateways

- https://www.geeksforgeeks.org/computer-networks/default-gateway-in-networking/

### Routers

- https://www.hpe.com/be/fr/what-is/router.html

### Routers and switches

- https://www.formip.com/pages/blog/switch-et-routeur-difference

### OSI layers

- https://fr.wikipedia.org/wiki/Mod%C3%A8le_OSI

### AI usage

AI was used as a learning and review tool during this project. In particular, it was used to:

- clarify networking concepts such as subnet masks, subnetting, routers, switches, and default gateways;
- help reason about and verify network configurations while solving the exercises;
- review and structure this README according to the requirements of the NetPractice subject.

AI-generated explanations and suggestions were checked and understood before being used. The final network configurations were solved and verified through the NetPractice interface.