Secure wireless communication is critical for society. The implementation of post-quantum cryptography in wireless systems will disrupt legacy implementations and evolve new protocols. Modifying systems and implementing new protocols benefits from experience with wireless concepts and commercial technologies like Wi-Fi, Bluetooth, and 802.15.4. This open-source project (github.com/potto216/wireless-games) combines a physical platform and software for Capture the Flag challenges on wireless systems. Participants can engage with either commercial wireless or simplified systems that focuses on core wireless concepts. The logical diagram of the physical system is shown in Figure 1. A constructed system is shown in Figure 2 and the internal components are shown in Figure 3. 

![logical_diagram_of_system](media/logical_diagram_of_system.png)

*Figure 1: Logical diagram of the system.*

The challenges include executing a "Man-in-the-Middle" attack on a Diffie-Hellman key exchange, jamming communication over a wired connection, or exploiting vulnerabilities such as nonce reuse.  By leveraging standard security tools, GNU Radio, software defined radios, and embedded wireless controllers, participants develop real-world skills in a secure, disconnected environment that prevents regulatory or Internet-related risks. The open-source software can run with a variety of hardware configurations with one documented in the repository.

![exterior_of_system](media/exterior_of_system.png)

*Figure 2: The physical system exterior.*


![interior_of_system](media/interior_of_system.png)

*Figure 3: Internal components of physical system in each of the three drawers.*

The system is configured using ansible with the playbooks in the repository potto216/automation-management. The challenges are configured with repositories such as potto216/arduino-examples: Examples focused on wireless uses with Arduino, potto216/esp-wireless, potto216/data-transfer-bench: Simple applications designed to test and benchmark data transfer over various communication links, potto216/BlueR-Test, and potto216/web-bluetooth-react. 

