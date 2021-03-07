# Turkish-Car-Plate-Regex
Turkish Car plate Regex

````
const regex = /^(0[1-9]|[1-7][0-9]|8[01])(\s)(([A-Z])(\s)(\d{4,5})|([A-Z]{2})(\s)(\d{3,4})|([A-Z]{3})(\s)(\d{2}))+$/g
const carPlate = "06 AB 203"
regex.test(carPlate)
````
