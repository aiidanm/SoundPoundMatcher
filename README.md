# Sound Pound credit union matcher


<img src="https://github.com/user-attachments/assets/7f196369-0a50-4b26-89fe-1c79403a2f46" alt="drawing" width="600"/>
<img src="https://github.com/user-attachments/assets/94d87bd5-cf3f-4e8a-bef2-236adeb1e37d" alt="drawing" width="200"/>


This project was commisioned by the SoundPound group with a brief to create a tool that will match an entered postcode with one of their credit unions eligible for the Transport for greater Manchester bus pass. 

After working with the Soundpound team to find out exactly what they wanted in the brief and how they wanted the design to look. I made the decision to stick with a JSON file containing Postcodes / credit union key value pairs. The tool will then use the npm "postcode" plugin that will extract / verify entered text. Convert it to a correct postcode format, i then run this throuhg the JSON file. I then use a seperate lookup table to match a Credit Unions name with its Logo, apply link and full Name. If any errors are found, then i will return an error. 

This tool was shared through a marketing campaign directly by Transport for Greater Manchester on Buses, social media and web. It was also shared directly with payroll partners including Manchester NHS foundation trust who forwarded this on in an email to their 28,000 members. 

The tool has allowed the SoundPound group to direct customers towrads it, and then each credit union recieves the correct applications. So far the tool has seen over 3000 unique visitors. 


The tool includes full dynamically created tests for every postcode key value pair in the JSON file. Testing for spacing entry issues, case differences, postcodes in overlapping common bond areas and outside of any eligible common bond. 

## Available Scripts

In the project directory, you can run:

### `npm start`


Runs the app in the development mode.\
Open [http://localhost:3000/](http://localhost:3000/) in the built-in Simple Browser (`Cmd/Ctrl + Shift + P > Simple Browser: Show`) to view your running application.

The page will reload automatically when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.


