# Face-Emotion-Attribute-Reader
The objective of this project is emotion detection and age prediction. It will take collection of JPG images from a source directory, submit each image and then produce a card for each face found showing the facial attributes (age and gender) along with the emotional scoring.
This project uses the Azure [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) Face API.

**Output**

![Example card](/media/example_card.png?raw=true "Example card")

**Setting up**

To run this project you'll need to create a `config.json` file in the root of the repository, this will contain the API Key for your cognitive services account. 

```json
{
    "apiKey": "<Face API Key>"
}
```

