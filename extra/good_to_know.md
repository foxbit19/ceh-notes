# Good to know concepts

##  N-tier architecture
- presentation tier - user interface
- logic tier - coordinates apps, commands
- data tier - storage

Tier-1: Developer machines - image creation, testing and accreditation

Tier-2: Testing and accreditation systems - verification and validation of image contents, signing images and sending them to the registries

Tier-3: Registries - storing images and disseminating images to the orchestrators based on requests

Tier-4: Orchestrators - transforming images into containers and deploying containers to hosts

Tier-5: Hosts - operating and managing containers as instructed by the orchestrator


## IoT architecture (from top to bottom)

- `application layer` - Delivery of various applications to different users in IoT
- `middleware layer` - Device management and information management
- `internet layer` - Connection between endpoints
- `access gateway layer` - Protocol translation and messaging
- `edge technology layer` - Sensors, devices, machines, and intelligent edge nodes of various types