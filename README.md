# Quran-API
### Quran API Documentation

#### Introduction
The Quran API allows developers to access recitations of the Quran by reciter and specific chapters.

#### Base URL
https://api.hideme.eu.org/quranrecit.php
#### Authentication
No authentication is required to access the API.

#### Endpoints

##### Retrieve Recitations
GET /quranrecit.php?id={reciter_id}&chapter_number={chapter_number}
###### Parameters
- id: The ID of the reciter.
- chapter_number: The number of the Quran chapter.

###### Response
The API returns an audio file of the recitation for the specified chapter by the chosen reciter.

###### Example
GET https://api.hideme.eu.org/quranrecit.php?id=3&chapter_number=36
#### Reciter IDs
1. Abdullah Awad al-Juhani
2. Abdullah Basfar
3. Abdur-Rahman as-Sudais
4. Ali Abdur-Rahman al-Huthaify
5. AbdulMuhsin al-Qasim
6. AbdulBari ath-Thubaity
8. Ahmed ibn Ali al-Ajmy
9. AbdulAzeez al-Ahmad
10. AbdulBaset AbdulSamad [Murattal]
11. AbdulWadud Haneef Aziz Alili
12. AbdulBaset AbdulSamad [Mujawwad]
13. Al-Hussayni Al-'Azazy (with Children)
14. Abdur-Razaq bin Abtan al-Dulaimi [Mujawwad]
15. Abdullah Khayat
16. Adel Kalbani
17. AbdulKareem Al Hazmi
18. Abdul-Mun'im Abdul-Mubdi'
19. Abdur-Rashid Sufi
20. Ahmad al-Huthaify
21. Abu Bakr al-Shatri [Taraweeh]
22. Abdullah Matroud
23. AbdulWadood Haneef
24. Ahmad Nauina
25. Akram Al-Alaqmi
26. Ali Hajjaj Alsouasi
27. Asim Abdul Aleem
28. Abdallah Abdal
29. Abdullah Ali Jabir

#### Chapter Number
1. Al-Fatiha (The Opening)
2. Al-Baqarah (The Cow)
3. Aal-E-Imran (The Family of Imran)
4. An-Nisa' (The Women)
5. Al-Ma'idah (The Table Spread)
6. Al-An'am (The Cattle)
7. Al-A'raf (The Heights)
8. Al-Anfal (The Spoils of War)
9. At-Tawbah (The Repentance)
10. Yunus (Jonah)
11. Hud (Hud)
12. Yusuf (Joseph)
13. Ar-Ra'd (The Thunder)
14. Ibrahim (Abraham)
15. Al-Hijr (The Rocky Tract)
16. An-Nahl (The Bee)
17. Al-Isra' (The Night Journey)
18. Al-Kahf (The Cave)
19. Maryam (Mary)
20. Ta-Ha (Ta-Ha)
21. Al-Anbiya' (The Prophets)
22. Al-Hajj (The Pilgrimage)
23. Al-Mu'minun (The Believers)
24. An-Nur (The Light)
25. Al-Furqan (The Criterion)
26. Ash-Shu'ara' (The Poets)
27. An-Naml (The Ant)
28. Al-Qasas (The Stories)
29. Al-Ankabut (The Spider)
30. Ar-Rum (The Romans)
31. Luqman (Luqman)
32. As-Sajda (The Prostration)
33. Al-Ahzab (The Combined Forces)
34. Saba' (Sheba)
35. Fatir (The Originator)
36. Ya-Sin (Ya-Sin)
37. As-Saffat (Those Ranged in Ranks)
38. Sad (Sad)
39. Az-Zumar (The Groups)
40. Ghafir (The Forgiver)
41. Fussilat (Explained in Detail)
42. Ash-Shura (The Consultation)
43. Az-Zukhruf (The Gold Adornments)
44. Ad-Dukhan (The Smoke)
45. Al-Jathiyah (The Crouching)
46. Al-Ahqaf (The Wind-Curved Sandhills)
47. Muhammad (Muhammad)
48. Al-Fath (The Victory)
49. Al-Hujurat (The Rooms)
50. Qaf (The Letter Qaf)
51. Adh-Dhariyat (The Winnowing Winds)
52. At-Tur (The Mount)
53. An-Najm (The Star)
54. Al-Qamar (The Moon)
55. Ar-Rahman (The Beneficent)
56. Al-Waqi'ah (The Inevitable)
57. Al-Hadid (The Iron)
58. Al-Mujadila (The Pleading Woman)
59. Al-Hashr (The Exile)
60. Al-Mumtahanah (She that is to be examined)
61. As-Saff (The Ranks)
62. Al-Jumu'ah (The Congregation)
63. Al-Munafiqun (The Hypocrites)
64. At-Taghabun (The Mutual Disillusion)
65. At-Talaq (The Divorce)
66. At-Tahrim (The Prohibition)
67. Al-Mulk (The Sovereignty)
68. Al-Qalam (The Pen)
69. Al-Haqqah (The Reality)
70. Al-Ma'arij (The Ascending Stairways)
71. Nuh (Noah)
72. Al-Jinn (The Jinn)
73. Al-Muzzammil (The Enshrouded One)
74. Al-Muddathir (The Cloaked One)
75. Al-Qiyamah (The Resurrection)
76. Al-Insan (Man)
77. Al-Mursalat (The Emissaries)
78. An-Naba' (The Tidings)
79. An-Nazi'at (Those who drag forth)
80. Abasa (He frowned)
81. At-Takwir (The Overthrowing)
82. Al-Infitar (The Cleaving)
83. Al-Mutaffifin (The Defrauding)
84. Al-Inshiqaq (The Splitting Open)
85. Al-Buruj (The Mansions of the Stars)
86. At-Tariq (The Morning Star)
87. Al-A'la (The Most High)
88. Al-Ghashiyah (The Overwhelming)
89. Al-Fajr (The Dawn)
90. Al-Balad (The City)
91. Ash-Shams (The Sun)
92. Al-Lail (The Night)
93. Ad-Duha (The Morning Hours)
94. Ash-Sharh (The Relief)
95. At-Tin (The Fig)
96. Al-'Alaq (The Clot)
97. Al-Qadr (The Power)
98. Al-Bayyinah (The Clear Proof)
99. Az-Zalzalah (The Earthquake)
100. Al-'Adiyat (The Courser)
101. Al-Qari'ah (The Calamity)
102. At-Takathur (The Rivalry in World Increase)
103. Al-'Asr (The Declining Day)
104. Al-Humazah (The Traducer)
105. Al-Fil (The Elephant)
106. Quraysh (Quraysh)
107. Al-Ma'un (The Small Kindnesses)
108. Al-Kawthar (The Abundance)
109. Al-Kafirun (The Disbelievers)
110. An-Nasr (The Divine Support)
111. Al-Masad (The Palm Fiber)
112. Al-Ikhlas (The Sincerity)
113. Al-Falaq (The Daybreak)
114. An-Nas (Mankind)
     
#### Rate Limiting
There are no rate limits currently enforced on this API.

#### Errors
- 400 Bad Request: If the request is missing required parameters or contains invalid parameters.
- 404 Not Found: If the requested recitation or chapter does not exist.

#### Support
For any inquiries or support, please contact mkhossain@duck.com.

#### Terms of Use
Usage of this API is subject to the terms and conditions outlined by the API provider.

#### Disclaimer
The API provider is not responsible for the accuracy or reliability of the recitations provided.

#### Versioning
Currently, there is no versioning of the API. Any changes to the API will be communicated directly to users.

This documentation provides a comprehensive overview of the Quran API, allowing developers to integrate Quran recitations into their projects efficiently.
