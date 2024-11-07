# Wireless-Toll-Fee-Collection-System
The system will include:  Vehicle – represents a vehicle passing through the toll. TollBooth – represents a toll booth that records tolls. TollSystem – represents the overall system responsible for the toll collection logic. WirelessReader – simulates a wireless reader that detects vehicle information
Explanation:
Vehicle Class: Represents a vehicle with basic properties like ID, license plate, and type.
TollBooth Class: Each toll booth has an ID, a toll fee, and a counter for how many vehicles have passed through. The ProcessToll method simulates collecting the toll fee.
WirelessReader Class: This simulates a wireless RFID or other wireless reader that identifies the vehicle passing through.
TollSystem Class: This class manages multiple toll booths and processes vehicles passing through them. It selects a random toll booth and processes the vehicle there.
Main Program: In the Main method, we create the system, add vehicles, and simulate the toll fee collection proces
