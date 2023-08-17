# IT-Project-4
## Implementing Active Directory Domain Services and Joining a Domain
### Objective
For the savn.local network, assign Carlos-S19-S1 as the domain controller. This project will implement the Active Directory Domain Services (AD DS) on this server by configuring its server roles and join the two other VMs to the virtual domain network.

### Description
Active Directory Domain Services (AD DS) provides a directory service that you can use for centralized secure management of your network. Installing AD DS on Carlos-S19-S1 will establish that server as the domain controller for the network that you constructed in Project 3.

------------------------------------------------------------------------------------------------------------------------------------------
## Introduction and Requirements

### Steps
1. Install AD DS / DNS-server on Carlos-S19-S1 and configure its server role as the domain controller.
2. Join Carlos-S19-S2 and Carlos-W01-C1 to the domain now controlled by Carlos-S19-S1.
- For a VM to access the network resources of the savn.local domain, the VM must be a member of the domain.

### Screenshots
1. Created the savn.local domain and promoted your Carlos-S19-S1 to be the domain controller.
2. Configured Carlos-S19-S2 to join the savn.local domain.
3. Configured your Carlos-W10-C1 VM to join the savn.local domain.
4. All VMs correctly joined the savn.local domain. From the Active Directory Users and Computers tool in Carlos-S19-S1, shows both
   Carlos-S19-S2 and Carlos-W10-C1 as members of the savn.local domain.

------------------------------------------------------------------------------------------------------------------------------------------

## License

    Copyright [2022] [Carlos Fuentes]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
