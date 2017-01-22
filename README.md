# bootTeeworlds
This automatically starts Teeworlds server as non-root when the Ubuntu server is shutdown and restarted using systemd



The reason why I created this is because auto starting Teeworlds server instance in Ubuntu on boot as a non-root is horribly complicated.

This auto starting requires "systemd" so make sure it's installed on your machine.

The reason why it needs to be non-root is because as root, the demo files recorded by the servers are stored in unintuitive places.

Basically, demos recorded by instances with root and without root are stored in different directories. (Seriously...?)
