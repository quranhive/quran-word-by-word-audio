# 📘 **QuranHive — Word-by-Word Qur’an Audio Dataset (Open Source)**

**Licensed under CC BY 4.0 • Requires Attribution**

The **full dataset (all audio files + metadata)** is hosted on **Hugging Face**, while this GitHub repo provides a lightweight entry point for developers, researchers, educators, and app builders.

---

The complete dataset is available on Hugging Face.

👉 **Hugging Face Dataset:**

This includes:

* **All word-by-word pronunciation audio files as mp3 format** from the full Qur’an
* **Metadata files** 

This GitHub repository serves as a public entry point to the data.

It includes licensing & attribution guidelines.

The attribution is mainly so that end users for products that have this data integrated have full knowledge of the source of the data and have the ability to report issues directly to us.

---

# 📦 **Download the Full Dataset**

👉 https://huggingface.co/datasets/quranhive/quran_word_by_word_audio

Word files follow this pattern:

```
{surah:03d}_{ayah:03d}_{word:03d}.mp3
```

Example:

* Surah 1 (Al-Fātiḥah), Ayah 1, Word 3 →
  `001_001_003.mp3`


# 🎧 About the Metadata

The full metadata is hosted on Hugging Face in two separate datasets, each serving a different purpose.

🔹 1. Word-to-Audio Mapping

Dataset:
👉 https://huggingface.co/datasets/quranhive/quran_word_by_word_audio_mapping

This dataset provides a mapping between each Qur’anic word and its corresponding pronunciation audio file.
It is stored in a flat .txt file, making it easy to read for:

Non-programmers

Excel users

Anyone who prefers a simple, tabular format without JSON parsing

🔹 2. Audio File Listing

Dataset:
👉 https://huggingface.co/datasets/quranhive/quran_word_by_word_audio_file_list

This dataset contains a full list of all audio files, stored as a CSV file.

📦 Storage

To keep this GitHub repository lightweight,
none of the full metadata files are stored here.
All datasets are hosted on Hugging Face for easy download and versioning.


---

# 📜 **License — CC BY 4.0 (Attribution Required)**

This dataset is released under the **Creative Commons Attribution 4.0 International** license.

You are free to:

* Use
* Adapt
* Modify
* Build upon
* Use commercially
  …as long as you **provide proper attribution**.

Full license: see `LICENSE`.

---

# 🙏 **Attribution Requirement**

If you use this dataset in a project, publication, app, or service, please credit:

> **"QuranHive Word-by-Word Audio Dataset — © QuranHive, licensed under CC BY 4.0"**
> [https://quranhive.com](https://quranhive.com)
> include the email: qh@quranhive.com (for users to report any issues)


---

# 🕌 **Religious Respect Notice (Non-Legal)**

This dataset contains **recitations of Qur’anic words**.
We kindly request that users treat it with respect and avoid:

* Mocking / satirical use
* Use in inappropriate contexts
* Use that alters sacred meaning

This is a moral request separate from the CC BY license.

---

# 🤝 **Updating Audio Files**

For a number of reasons, we may apply batch updates to audio files. Typically these updates are small and infrequent.

However, if we identify audio files that are below standards (either through user reports or internal validation), then we certainly aim to apply fixes.

Accordingly, we intend to keep the word-by-word audio dataset (hosted on Hugging Face) up to date at all times.

These are some of the quality considerations for when we would consider updating an audio file:

* Inaccuracy
* Mispronunciation
* Wrong word
* Tajweed weakness
* Audio quality

---

# 🤝 **Reporting Issues**

We strongly encourage feedback. If you come across any issues with any of the audio files, please report to: qh@quranhive.com

Refer to the quality considerations mentioned above.

---

# 🌍 **Why Open Source This?**

This dataset is released as **a sadaqah jariyah** and in the spirit of enabling:

* Qur’an teachers & students
* Arabic learners
* App developers
* Islamic education institutions

QuranHive remains the leading **Qur’an learning platform**, and this dataset supports the wider Ummah with foundational resources.

---

# ⭐ **Acknowledgements**

This dataset was produced and curated by **QuranHive**.
May Allah make it a source of continuous reward for everyone involved.