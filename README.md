# portfolioproject
Automobile Class Methods and Pseudo Code Class: Automobile Method: AddVehicle Definition: public String AddVehicle(String autoMake, String autoModel, String autoColor, int autoYear) Pseudo Code:

Create a new vehicle object with the given parameters.
Check if the vehicle already exists in the list: a. If it exists, return a message indicating the vehicle already exists. b. If it doesn't exist, add the vehicle to the list and return a success message. Method: RemoveVehicle Definition: public String RemoveVehicle(String autoMake, String autoModel, String autoColor, int autoYear) Pseudo Code:
Iterate through the list of vehicles.
For each vehicle, check if the make, model, color, and year match the given parameters: a. If a match is found, remove the vehicle from the list and return a success message. b. If no match is found, return a message indicating no matching vehicle was found. Method: UpdateVehicle Definition: public String UpdateVehicle(String existingAutoMake, String existingAutoModel, String newAutoMake, String newAutoModel, String newAutoColor, int newAutoYear) Pseudo Code:
Iterate through the list of vehicles.
For each vehicle, check if the make and model match the existing parameters: a. If a match is found, update the vehicle's details with the new parameters and return a success message. b. If no match is found, return a message indicating no matching vehicle was found. Method: GetVehicleDetails Definition: public String GetVehicleDetails(String autoMake, String autoModel) Pseudo Code:
Iterate through the list of vehicles.
For each vehicle, check if the make and model match the given parameters: a. If a match is found, return the details of the vehicle. b. If no match is found, return a message indicating no matching vehicle was found. Method: ListAllVehicles Definition: public List ListAllVehicles() Pseudo Code:
Initialize an empty list to store vehicle details.
Iterate through the list of vehicles.
For each vehicle, add its details to the list.
Return the list of all vehicle details.
