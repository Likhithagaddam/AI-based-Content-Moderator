# AI-based-Content-Moderator
The exponential growth of online platforms has been accompanied by a surge in usergenerated content, including harmful material such as hate speech. The multilingual nature of
this content poses significant challenges for effective moderation, particularly when different languages are involved. In order to properly handle multilingual user-generated hate speech
content, the study suggests an AI-based content moderation system that makes use of machine learning techniques and Natural Language Processing (NLP). The system performs three key
tasks: 
1.Language identification
2.Hate speech detection
3.Target identification

It learns from vast multilingual data, identifies harmful content patterns, and targets specific individuals orgroups. This system ensures a safer online environment and continuous improvement through learning and adaptation.

#Subtask A: Language Identification
This sub-task addresses the need for accurate language identification in multilingualDevanagari texts. The goal is to classify a given sentence into one of four languages:Nepali, Marathi, Sanskrit, or Hindi. These languages share significant linguisticsimilarities due to their common script, making accurate distinctions challenging fortraditional methods. This task aims to develop a robust model capable of overcoming this linguistic overlap, providing a necessary foundation for subsequent content analysis.

#Subtask B: Hate speech detection
In this subtask, hate speech in Devanagari text is automatically detected and classified as either containing hate speech or not. Detecting hate speech in these languages isdifficult due to its context-dependent nature, use of sarcasm, indirect references,cultural expressions, and code-mixing. This task aims to develop a tailored detection mechanism accounting for these nuances. 

#Subtask C: Target identification
This sub-task aims to identify the targets of hate speech within hateful Devanagari text,categorizing them as "individual", "organization" or "community." Identifying targets is essential for understanding the impact of harmful content. However, targetidentification in Devanagari texts is challenging due to implicit mentions. This task focuses on developing a reliable classification mechanism to accurately identify these targets.

The models used to inculcate language detection is fastText. The models employed for hate speech detection is HateSpeech-CNERG (with fine-tuning). The model used for target identification is mBERT. The Precision-Recall Area Under Curve (PR-AUC) is utilized to assess the performance of the models in predicting the number of correct positive predictions made
by the models. The PR-AUC curve for fastText is 0.92, Hate-speech-CNERG is 0.39, and mBERT is 0.78. This study presents a scalable and efficient method for managing online toxicity by moderating multilingual content, thereby enhancing secure digital interactions and a robust online ecosystem.
