Hi,

This is Team Ui Unified and we are working on the folowing theme:  Automate for a cause

Our idea is to avoid food waste at various functions conducted in India (whose number is actually humongous!!)

Due to poor planning, a large amount of food gets wasted everyday in these functions. People are so lazy that they would rather throw away the food instead of going through the process of finding an NGO and donating.

Our product basically drives their laziness away. If a person who has excess food enters his contact details, pincode and amount of food in our product, a mail will automatically be sent to nearby NGOs with the above mentioned details so that they can pick up the food.

STEPS:
1. Enter your name
2. Enter your phone number
3. Enter the amount of food to be donated
4. Enter the pincode you are currently in (For demo, we are using values 600001-600050)

FUNCTIONALITY:
Once the pincode is entered, Uipath compares an excel sheet which contains all the NGOs in that specific city (in our case chennai), along with their pincodes.
If there is a match in user entered pincode and the NGO pincode in excel sheet, then the email IDs of that specific NGOs are extracted.
After extraction, the user given details i.e contact details and the amount of food are sent in a mail to that specific NGO
Thus, the person from NGO can come and collect food from donator which will be useful to many people.