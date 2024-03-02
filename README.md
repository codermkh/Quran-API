# Quran-API
### Quran API Documentation

#### Introduction
The Quran API allows developers to access recitations of the Quran by reciter and specific chapters.

#### Base URL
https://hideme.eu.org/developer/quranapi.php
#### Authentication
No authentication is required to access the API.

#### Endpoints

##### Retrieve Recitations
GET /quranapi.php?id={reciter_id}&chapter_number={chapter_number}
###### Parameters
- id: The ID of the reciter.
- chapter_number: The number of the Quran chapter.

###### Response
The API returns an audio file of the recitation for the specified chapter by the chosen reciter.

###### Example
GET https://hideme.eu.org/developer/quranapi.php?id=3&chapter_number=2
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

#### Rate Limiting
There are no rate limits currently enforced on this API.

#### Errors
- 400 Bad Request: If the request is missing required parameters or contains invalid parameters.
- 404 Not Found: If the requested recitation or chapter does not exist.

#### Support
For any inquiries or support, please contact support@hideme.eu.org.

#### Terms of Use
Usage of this API is subject to the terms and conditions outlined by the API provider.

#### Disclaimer
The API provider is not responsible for the accuracy or reliability of the recitations provided.

#### Versioning
Currently, there is no versioning of the API. Any changes to the API will be communicated directly to users.

This documentation provides a comprehensive overview of the Quran API, allowing developers to integrate Quran recitations into their projects efficiently.
