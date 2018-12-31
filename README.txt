This dataset is a compilation of Hadiths from Kutub al-Sittah (The Six Books):

1) Sahih Bukhari صحيح البخاري - Hadith collected by Imam Bukhari (d. 256 A.H., 870 C.E.)
2) Sahih Muslim صحيح مسلم - Hadith collected by Muslim b. al-Hajjaj (d. 261A.H., 875 C.E.)
3) Sunan an-Nasa'i سنن النسائي - Hadith collected by al-Nasa'i (d. 303 A.H., 915 C.E.)
4) Sunan Abu-Dawood سنن أبي داود - Hadith collected by Abu Dawood (d. 275 A.H., 888 C.E.)
5) Jami at-Tirmidhi جامع الترمذي - Hadith collected by al-Tirmidhi (d. 279 A.H, 892 C.E)
6) Sunan ibn-Majah سنن ابن ماجه - Hadith collected by Ibn Majah (d. 273 A.H., 887 C.E.)

Each directory corresponding to one of the six books contains a set of XML files of
the individual Hadiths found in that book. Each XML file contains the following
attributes:

    * id: A unique identifier for the Hadith
    * source: The book in which the Hadith can be found
    * chapter: The chapter in the book containing the Hadith
    * chain-index: The chain of narrators. Each number corresponds to the ID of
      a narrator as found in the Muslim Scholars Database (http://muslimscholars.info/)
    * arabic-text: The Hadith in Arabic
    * english-text: The Hadith in English (NOTE: some files are missing an
      english translation)

MD5 checksums of each file can be found in the checksums directory ordered by
their corresponding book. These can be used to verify the integrity of the files
provided.

Compressed archives can be found in the archives directory.

Data: This data was mined from the comprehensive Hadith Database at http://qaalarasulallah.com/

DISCLAIMER: The dataset has not been fully validated and therefore may require further
            processing before use. I make no guarantees with respect to its
            validity.
