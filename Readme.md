# Get Data on Address IP

This is a simple HTML project that fetches and displays the user's public IP address and related geolocation data using the `ipify` and `ipapi` APIs.

## Features

- **Fetch Public IP**: The application retrieves the user's public IP address.
- **Display Geolocation Data**: It fetches and displays additional geolocation data related to the IP address, including country, region, city, and more.

## How It Works

1. The script starts by displaying "loading..." while the data is being fetched.
2. It fetches the public IP address using the `ipify` API.
3. Once the IP address is retrieved, it fetches additional data related to that IP using the `ipapi` API.
4. The IP address is displayed in the `<p>` element, and the geolocation data is formatted and displayed in a `<pre>` element.

## Technologies Used

- **HTML**: For the basic structure of the page.
- **JavaScript**: For fetching the IP address and geolocation data from external APIs.
- **APIs Used**:
  - [ipify](https://www.ipify.org/): To get the public IP address.
  - [ipapi](https://ipapi.co/): To get geolocation data based on the IP address.

## How to Use

1. Clone the repository or download the HTML file.
2. Open the HTML file in any web browser.
3. The page will automatically display your public IP address and related geolocation data.

## Example Output

```json
{
  "ip": "123.456.78.9",
  "city": "Sample City",
  "region": "Sample Region",
  "country": "Sample Country",
  "postal": "12345",
  "latitude": 12.345678,
  "longitude": -12.345678,
  "timezone": "Sample/Timezone",
  "org": "Sample Organization"
}
