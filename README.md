# Creating a textual knowledge base from PhD lectures in order to leverage professor's insights using semantic search
Repository contains transcriptions of my PhD lectures in Mathematical Logic and Computer Science. The solution involves fine-tuning pretrained MathBERT transformer in order to be able to efficiently search through video material based on textual semantic search.

You can find the complete solution with 35+ hours of lectures in Mathematical Logic searchable by fine-tuned MathBERT model hosted on [HuggingFace Space](https://huggingface.co/spaces/TamedWicked/math-lectures-semantic-search), or here if you prefer a [direct url](https://tamedwicked-math-lectures-semantic-search.hf.space/).

Each queries will result in top 5 results with relevant youtube links with exact timestamps where the speech happened during the lecture.

It is a work in progress as Google Colab regularly blocks my runtimes due to me abusing their free service. :)
Once completed it will contain 35+ full lectures of text, completely searchable through semantic similarity or by just plainly querying questions that come up during my study of the material.

The idea occured to me after my initial [article](https://www.linkedin.com/posts/matija-pajas-0b2a46143_how-to-get-more-out-of-your-meetings-using-activity-7042462394224119808-fZMB?utm_source=share&utm_medium=member_desktop) about semantic search.

All lectures are available on the official university youtube channel from where the audio files are downloaded.
