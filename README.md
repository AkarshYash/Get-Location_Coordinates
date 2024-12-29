# get_location_coordinatesSure, 

```
# Phone Number Tracker

This Python script allows you to track a phone number and retrieve its associated address along with location coordinates using NumVerify API and Google Maps Geocoding API.

## Prerequisites

Before running the script, you need to obtain API keys for both NumVerify and Google Maps Geocoding services. You can obtain these keys by signing up on their respective websites:

- [NumVerify](https://numverify.com/)
- [Google Maps Platform](https://cloud.google.com/maps-platform/)

Once you have obtained the API keys, replace the placeholder API keys in the script with your own keys.

## Installation

1. Clone the repository or download the script directly.
2. Make sure you have Python installed on your system.
3. Install the required packages using pip:
   ```
   pip install requests
   ```
4. Replace the placeholder API keys in the script with your own keys.

## Usage

Run the script using Python:

```
python phone_tracker.py
```

You will be prompted to enter the phone number you want to track. Once you enter the phone number, the script will validate it using the NumVerify API. If the phone number is valid, you will be asked to enter the associated address. The script will then use the Google Maps Geocoding API to retrieve the location coordinates for the provided address.

## Example

```
+91************: +91-*************
Phone number is valid.
Enter the address associated with the phone number: New York City
Location coordinates for the provided address: Latitude: 40.7127753, Longitude: -74.0059728
```

## Contributing

If you have any suggestions or improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
``` 
