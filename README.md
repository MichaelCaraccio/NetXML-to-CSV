# NetXML-to-CSV

## Synopsis

Convert a .netxml file into CSV file. 
For those who use Kismet and want to display networks on a Google Maps for example.

CVS file with 5 columns : ESSID, MAC Address, encryption type, latitude, longitude

## Code Example

Convert every network into a csv file : 
```
python3 main.py file.netxml result.csv
```

Convert only WEP encryption networks :
```
python3 main.py file.netxml result.csv WEP
```
Convert only WPA+AES-CCM encryption networks :
```
python3 main.py file.netxml result.csv WPA+AES-CCM
```

## Installation
```
git clone https://github.com/MichaelCaraccio/NetXML-to-CSV.git
```

## License
MIT
