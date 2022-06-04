# Roadmap
Roadmap for Webapp goals, and and ideally documentation.

Setup dev and pm environments
    connect text editor to github

Create Threat intelligence API
    Deploy Honeypot sensor
        Identify sensor requirements
            Identify Hosts which provide DMZ and dedicated IP at lowest cost
            
            identify which VPS size is appropriate for the sensor. And approximate bvandwidth use

            research hosting providers policies.
        Custom ISO
            Identify parts of stock (tpotce) sensor which ship telemetry to tmobile and remove them 

            forward all management ports over one of the dedicated management ports, whitelist it
                Disable any low information sensors

                Create additional port rules for low information ports
