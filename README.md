# Bitmex-direct-trading-panel
Allows you to send orders even when servers are overloaded, using direct API requests on a GUI. 

Made with Python Tkinter and modified from the original bitmex marketmaker script. 

When the servers are overloaded on bitmex, there is a chance that orders sent through API will still go through. During load shedding,  orders from the bitmex web platform are first to be discarded. 

This tool here is useful if you want to try to send orders during overloaded situations (good for mopping up the orderbook), or if you just want a simple GUI. 
