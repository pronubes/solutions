With this Solution, you can use artificial intelligence via the OpenAI API to automatically classify and structure free-text shift log entries into a standardized JSON object.

Two connections are included.
The Web-Trigger connection provides a lightweight [**debug and test page**](/services/AI%20Shift%20Log%20Classifier%20API/shift-log-classifier/ui) for entering sample shift log entries to validate the classifier.
The website forwards the input to the AI endpoint defined in the AI-Trigger connection.
There, the data is automatically processed, sent to the OpenAI API, and the relevant fields are extracted and categorized.
The resulting JSON object is then transmitted back to the test page and displayed.

##### Notes
- You can find your organization and project ID at [**platform.openai.com**](https://platform.openai.com/) in the settings under the **General** menu item.
- The model **GPT-5-mini** is configured by default.
