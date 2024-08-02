# Salat-script

A Bash script to fetch and display Islamic prayer times based on geographical coordinates using the Aladhan API with the Egyptian General Authority of Survey method.

## Prerequisites

Ensure you have the following installed on your system:
- `curl`
- `jq`

You can install them using:
```bash
sudo apt-get install curl jq
```

## instalation 
1 . Clone the repository to your local machine:
``` bash
git clone https://github.com/RamdaniRamdane/Salat-script.git
```

2 . Navigate to the project directory:
```bash
cd Salat-script
```

3 . Make the script executable:
```bash
chmod +x salatv1
```

## Usage

### The script requires three arguments 
The action you want to perform (e.g., nextSalat, nextSalatName, allSalat, Fajr, Dhuhr, Asr, Maghrib, Isha).
Latitude of the location.
Longitude of the location.

### Examples
To get the name and time of the next prayer:
```bash
./salatv1 nextSalat 36.6373 4.2041
```

To get the name of the next prayer:
```bash
./salatv1 nextSalatName 36.6373 4.2041
```
To get all prayer times for the day:
```bash
./salatv1 allSalat 36.6373 4.2041
```
To get the time for Fajr prayer:
```bash
./salatv1 Fajr 36.6373 4.2041
```
To get the time for Dhuhr prayer:
```bash
./salatv1 Dhuhr 36.6373 4.2041
```
To get the time for Asr prayer:
```bash
./salatv1 Asr 36.6373 4.2041
```
To get the time for Maghrib prayer:
```bash
./salatv1 Maghrib 36.6373 4.2041
```
To get the time for Isha prayer:
```bash
./salatv1 Isha 36.6373 4.2041
```
Options

    nextSalat: Display the name and time of the next prayer.
    nextSalatName: Display the name of the next prayer.
    allSalat: Display all prayer times for the day.
    Fajr: Display the time for Fajr prayer.
    Dhuhr: Display the time for Dhuhr prayer.
    Asr: Display the time for Asr prayer.
    Maghrib: Display the time for Maghrib prayer.
    Isha: Display the time for Isha prayer.

