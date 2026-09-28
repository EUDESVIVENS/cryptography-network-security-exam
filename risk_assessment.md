# Risk Assessment and Project Setup

## a. Assets, Vulnerabilities, and Consequences

### Identified Assets
* **Student Records Database:** The sensitive personal, academic, and administrative data stored centrally.
* **Central Records Server:** The physical or virtual infrastructure hosting the database.
* **Inter-Campus Network Infrastructure:** The communication channels used to transmit files between the two campuses.


### Identified Vulnerabilities and Consequences
1. **Weak Staff Passwords**
   * **Consequence:** An attacker could easily brute-force or guess a staff member's password, leading to unauthorized access to the system and data theft.
2. **Unencrypted Inter-Campus File Transfers**
   * **Consequence:** Attackers on the network can intercept transmissions (man-in-the-middle attack) to read or alter student records while they are moving between campuses.
3. **Guest Network Access to the Records Server**
   * **Consequence:** Anyone sitting in the campus lobby or parking lot connected to the guest Wi-Fi could directly scan, attack, or exploit the central server.
