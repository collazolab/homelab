# homelab

Extensive information about the homelab and its setup can be found on the locally hosted wiki.  This will serve as a placeholder for the time being.


To Do List

    *Ansible Environment*
    Explore VS Code
    ~Bind VS Code and Github~
    Create Ansible playbooks 
    Run, Test and Schedule Ansible playbooks via Semaphore
    Add more nodes to master Inventory file
    Get rid of other Ansible instances
    Clean up and centralize SSH stuff
    
    //*Power Migration*
    Plug in alternate UPS
    Connect R610 2nd PSU to alt. UPS
    Connect R510 2nd PSU to alt. UPS
    Static IP reservations for essential VMs
    Static IP reservations for PVE nodes
    Backup OPNsense config
    Power down unneccessary stuff
        UNVR
        Beelink
        CM4
    get alt. UPS checked into nut-server
    Pull the PDU plug on UPS1
    Change battery in UPS1
    Plug new 0U PDU into UPS1
    monitor nut-server
    Test that everything came back up successfully

    //*R210 PVE Node*
    Troubleshoot booting issue
        Last things changed - new NIC, ram not seated?
        idrac logs?
    Load PVE onto least performant SSD
    name it r210-pve1?
    Static IP
    alerting email address?
    take inventory of ram
    spin up opnsense vm
    add datastore
    add network bridges for physical and virtual nics
    
    //*Rack Cleanup*
    After power migration, run power cables through CMA's where possible
    Remove 2nd PSU cables
    Run Power cables down the right side through channels where possible
    Install Rack LEDs
    Rack mini switch on shelf?
    Try to bind patch panel runs down the left side
    Swap out cat6 runs for longer black cables where needed
    Run network cables through CMA's where possible
    try to label cables where possible with standardized source and destination tags
    
    

