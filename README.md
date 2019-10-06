Babble
======

Update (2019-10-06): Google has removed Babble from Google Play due to an alleged trademark infringement. I don't have time to investigate this. The only way to obtain the Babble app now is to download the apk from https://github.com/Kaljurand/babble/releases. However, there is an app called Babblemore now available on Google Play: <https://play.google.com/store/apps/details?id=com.appspot.k6nele.android.babblemore>. It is was developed in early 2013 as an extension of Babble but this work was never finished, and never published neither as source code nor on Google Play. Its main improvement over Babble is the inclusion of a larger and more multilingual set of phrases (based on the MOLTO Phrasebook:
https://github.com/GrammaticalFramework/gf-contrib/tree/master/phrasebook). It is available now on Google Play to offer a simpler way to install a Babble-like app and show the possible extensions to the original idea behind Babble. Note that Babblemore can contain various bugs due to its unfinished nature.

---

Babble is an Android app that shows you short phrases/sentences in many different languages and you'll have to
pronounce them quickly (in 4 seconds) and correctly. Babble will give you feedback in the form of
an edit distance between the transcription of your pronunciation and the original phrase.

Components of a typical practice session:

  - tap on the big yellow button and read out loud the displayed text (in the correct language)
  - tap on the text to try again
  - tap on the language label (under the phrase) to send the phrase to Google Translate
  - tap on "Phrases" to see the history of phrases, sortable by various parameters
  - tap on a phrase to listen to its correct pronunciation
  - tap on "Plot" to see the graph of your error levels in different languages

Babble uses the services of speech-to-text and text-to-speech that are available via standard Android APIs.
The apps that provide these services (e.g. Google Voice Search for speech-to-text,
various TTS engines for text-to-speech) have to be installed separately in case they are not
already pre-installed.

The current version is a prototype.
The core of it was developed in October 2012 by 3 Android enthusiasts over a weekend in the beautiful library of Genk,
Belgium, as part of the V Hack Android hackathon.

For more information see

  - Google Play page: https://play.google.com/store/apps/details?id=be.lukin.android.babble
  - original project page (not maintained): http://vhackandroid.wikia.com/wiki/Babble
