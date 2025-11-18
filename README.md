# Language-Translator-Project
This project focuses on building a multilingual language translation system using Meta’s NLLB-200 model and a Gradio interface, enabling translation across more than 200 global languages.NLLB is a state-of-the-art multilingual AI model developed by Meta AI that can translate 200+ languages with high accuracy, including low-resource languages that are usually underrepresented in machine translation.




This translation tool is designed to be efficient, scalable, and highly adaptable, making it suitable for academic use, multilingual communication, and future expansion.A user-friendly Gradio interface is integrated to enable easy text input, language selection, and real-time translation output, making the system accessible to all users.The system integrates a transformer-based encoder–decoder architecture that understands context, grammar, and semantics, producing natural translations instead of word-to-word outputs.




A comprehensive language map of 204 languages is implemented, enabling precise mapping between readable language names and their internal model codes.t demonstrates how modern NLP models can be deployed efficiently within a lightweight UI, allowing even non-technical users to access advanced machine translation technology.The project highlights the importance of low-resource language support, as NLLB-200 is specifically designed to translate underrepresented languages with better quality than traditional models.




It begins by installing and loading essential libraries like Transformers, SentencePiece, and Gradio, then initializes the NLLB-200 distilled 600M model along with its tokenizer for natural-language translation.A comprehensive LANGUAGE_MAP dictionary is created, containing human-readable language names mapped to their correct NLLB language codes, forming the backbone of the multilingual selection system.




The project defines a translation function that uses the HuggingFace pipeline to process input text, automatically detect the selected source and target languages, and generate translated output via the NLLB model.A user-friendly Gradio interface is implemented, featuring dropdown menus for choosing languages, a textbox for entering text, and an output box to display translations, all structured within an intuitive and interactive web-based UI.




The implementation highlights the efficiency of modern NLP models, the importance of proper language mapping, and the simplicity of deploying AI-driven tools for everyday use.Overall, the project demonstrates the integration of state-of-the-art translation technology with a clean, interactive front-end, allowing users to seamlessly translate text between hundreds of languages using a single unified application.
