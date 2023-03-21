# Creating a textual knowledge base from PhD lectures in order to leverage professor's insights using semantic search
Repository contains transcriptions of my PhD lectures in Mathematical Logic and Computer Science. The solution involves fine-tuning pretrained MathBERT transformer in order to be able to efficiently search through video material based on textual semantic search.

You can find the complete solution with 35+ hours of lectures in Mathematical Logic searchable by fine-tuned MathBERT model hosted on [HuggingFace Space](https://huggingface.co/spaces/TamedWicked/math-lectures-semantic-search), or here if you prefer a [direct url](https://tamedwicked-math-lectures-semantic-search.hf.space/).

Each query will result in top 5 results with relevant youtube links with exact timestamps where the speech happened during the lecture.

It is a work in progress as Google Colab regularly blocks my runtimes due to me abusing their free service. :)
Once completed it will contain 35+ full lectures of text, completely searchable through semantic similarity or by just plainly querying questions that come up during my study of the material.

The idea occured to me after my initial [article](https://www.linkedin.com/posts/matija-pajas-0b2a46143_how-to-get-more-out-of-your-meetings-using-activity-7042462394224119808-fZMB?utm_source=share&utm_medium=member_desktop) about semantic search.

All lectures are available on the official university youtube channel from where the audio files are downloaded.

## A few notable search results:

### Query: Koje strukture su izomorfne?

|       | Speech                                                                          | start_link                          |
|------:|:--------------------------------------------------------------------------------|:------------------------------------|
|  7092 | ali strukture koje su elementarno ekvivalente ne moraju biti izomorfne.         | https://youtu.be/3YoHR8CGU-4?t=2308 |
|  8856 | Dakle, mogu trivijalno uzeti dvije strukture koje jesu izomorfne,               | https://youtu.be/Y4sFFGs6rt4?t=490  |
|  8926 | Dakle, to je zapravo pravi izomorfizam dvije strukture.                         | https://youtu.be/Y4sFFGs6rt4?t=804  |
|  6689 | koji je izomorfan ovoj manjej strukturi.                                        | https://youtu.be/3YoHR8CGU-4?t=470  |
|  6181 | Dakle, ne mora biti, postoje i strukture prvog rada koje nisu normalne,         | https://youtu.be/QWzjU9Tdt4Y?t=825  |
|  6698 | Svakako važan teorem je da izomorfne strukture,                                 | https://youtu.be/3YoHR8CGU-4?t=500  |
|  8724 | Ali gdje je bilo važno da su normalne strukture?                                | https://youtu.be/hF6Zm4IUYGQ?t=2548 |
| 12286 | Dakle, ove dvije strukture su očito elementarno ekvivalentne, čak su izumorfne, | https://youtu.be/UXihhCqIjkg?t=1779 |
|  6586 | Dakle, imamo dvije strukture i onda zapravo homomorfizam nije                   | https://youtu.be/3YoHR8CGU-4?t=10   |
|  8844 | Ako su konačno izomorfne i konačne, onda su izomorfne.                          | https://youtu.be/Y4sFFGs6rt4?t=438  |

### Query: Elementarno ekvivalentne strukture

|       | Speech                                                                  | start_link                          |
|------:|:------------------------------------------------------------------------|:------------------------------------|
| 17793 | I to su elementarno ekvivalentne strukture.                             | https://youtu.be/8yu-sTrLbyw?t=1739 |
|  6701 | Izomorfne strukture jesu elementarno ekvivalente.                       | https://youtu.be/3YoHR8CGU-4?t=509  |
|  8366 | Dakle, dvije strukture su elementarno ekvivalentne                      | https://youtu.be/hF6Zm4IUYGQ?t=476  |
|  7091 | Znači, strukture koje su elementarni jesu elementarno ekvivalentne,     | https://youtu.be/3YoHR8CGU-4?t=2305 |
| 17772 | ali moraš biti u nekoj elementarno ekvivalentnoj strukturi.             | https://youtu.be/8yu-sTrLbyw?t=1632 |
| 12278 | Ali ima, ima pisanja. Dvije sigma strukture su elementarno ekvalentne,  | https://youtu.be/UXihhCqIjkg?t=1720 |
|  5278 | Elementarno je ekvivalentan soljnih svijeta.                            | https://youtu.be/89RDceRtiXA?t=1512 |
|  7092 | ali strukture koje su elementarno ekvivalente ne moraju biti izomorfne. | https://youtu.be/3YoHR8CGU-4?t=2308 |
|  4757 | onda će biti elementarno ekvivalentni.                                  | https://youtu.be/9mInaqY-szk?t=1470 |
|  6707 | pa tako je elementarno ekvivalenciju.                                   | https://youtu.be/3YoHR8CGU-4?t=533  |
