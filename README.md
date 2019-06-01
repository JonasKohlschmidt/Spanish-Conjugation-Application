# Spanish-Conjugation-Application
This project is an application to ease the memorization and learning of the numerous (irregular) conjugations in the tenses of the Spanish language. The verbs and tenses of choice can be chosen and are tested in a quiz, and the progress is monitored over time.

The application combines two main ideas:
1) The verbs to study can be chosen freely, e.g. to follow a language book or simply learn the most used verbs in Spanish. To achieve this a data scraper was implemented which downloads and saves all conjugations of a chosen verb from spanishdict.com. This allows for building an individual stack of verbs to study.
2) Whenever a verb is tested in a quiz the application keeps track wether the answer was correct or not. The so collected data allows for the following:
- Creating learning curves to monitor the progress in different tenses. This offers the user a precise overview over his performance in each tense
- The probability of appearance of a verb in a quiz depends on the users performance of that verb in the chosen tense. Verbs that the user performs poorly with are more likely to be tested than verbs that user performs good with.

Code will be uploaded as soon as functional GUI has been implemented (hopefully soon =) ).
