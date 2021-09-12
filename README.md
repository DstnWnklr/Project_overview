# Project overview

This is an overview of the projects I developed during my four semesters at the Hochschule Harz. This overview will focus primarily on my computer science classes.

## 1. Semester ##

###### Java ######

Every week in the first Semester, we had to solve a specific task. The solutions were necessary to pass the exam. Therefor we had to work together in groups of two people. The tasks where basic exercises to learn Java

One of these task was to generate a GUI with 500 x 500 px. After that the program should position 20 points randomly on the interface. The user should now have the opportunity, to choose between different comparison methods. After the comparison the program should connect the dots depending on the distance. 
The comparison methods:

• Lexicographically: first the X-coordinate, if they are the same, the Y-coordinate

• Lexicographically: first the Y coordinate, if it is the same, the X coordinate

• Compare the distance of the points to the origin

• Comparison of the distance of the points to the center of the drawing area


For my solution I used the *Scanner* to ask the user for the comparison method. 
![image_1](https://db3pap003files.storage.live.com/y4m06PQSnyTJPzzk3Z-Eu4XvLSP61gve151w-TaroYxQFYa5VBrfxM-noXi4t7s8-NqpN8fQLH6MG0WN1f-tcLGuNwY_cd_EM42OtV3MTxMucAOYWqFJoegQFevy4qjwNtIcpnUML4z7YnB-INStbgiJYND9Jc5RaXD396kDl79FYBkH7UHu3bw_iQTlsO4_UN6?width=1392&height=754&cropmode=none)

A new class *Zeichenflaeche* created the GUI with the JFrame extension.
![image_2](https://db3pap003files.storage.live.com/y4mnxb8Mh_jezv7iF0XjOUVVpfuSpk965tuhqd7ACn86UwA55dSsac0pjoZdVOzgphDkCr3rf1qio5sdiVVs6LfcYp9VCsMeEZqM4SZUOouRchPLPwM7MAFtInyTlqy9pmr-0hWfYrOEE0_k_2Rqybo6WHYraXAXDqpVD5pSOTTK0GK9EK-meUMyCAj-S_tN0Bz?width=1810&height=1148&cropmode=none)

Another class was used to create different methods for the varying comparison methods. As an example you can see the solution for the first lexicographically comparison.
![image_3](https://db3pap003files.storage.live.com/y4mfAl42BiONfqVr27bpdlf7J16eO0zTebVWFx8zOEL1g83b3MZEF0Wk0M50zuBj4MFHesNezI6x3Wf8wNjR4s59IpNphVKPppdPlmRx_6z8SXrRoAcyjtbXZiogDv5TDWMrUIL5TAawv83cyGFp3KFulAgMHZd7vRY1v5lGKKaUHM6veETZmR7UwP9NkK6krfF?width=1996&height=1102&cropmode=none)


###### HTML and CSS ######

The first website was a standard non responsive HTML and CSS side with some JavaScript. The topic was self-selectable. I decided to create a website for the Netflix-series *Tales by Light*. The website contained a menu and three subpages.
![image_4](https://db3pap003files.storage.live.com/y4muBvldUI7j6oWMWXEqdcL9XY9GGHgQJOrO-3Hn7msN7MUR_3Xvq8kB7m-MM0k-bTDvHsjpgpBuaLzPPx589yn_p2Te1idf2h0lCYE1_nDuG2WTUNxuAE8huX4PfUyOqkKQHRLtzMnjRMgDeIBk8oBYt9mcfC4QSlzFqzBYXpYf5PFc59Gdzg2sVmKCWU6uIhm?width=1974&height=1172&cropmode=none)

Additionally I added a video-player and a slideshow, to represent the images of the photographers. 
![image_5](https://db3pap003files.storage.live.com/y4mzCrMhLrJbqI4aTcHiwtdWVtP4V6kV-8wxDx4yPLSnRPQjLTGsqltyBhGUhM6M_laFoPD2VeUXd7znHlM7_82hxsv4ZFAsNVVqa4YaMH2zz9ewHDCCPuVPiBsQoU1mXoMmwEroTtp_SwbEuUW0DEI57DLBF1QbPcHelLyVkY62666FRfiLdYcLrzM22NlrvQ2?width=1298&height=652&cropmode=none)

## 2. Semester ##

###### Java ######

The second semester had a similar Schedule then the first semester. Therefor we had to solve a task for every week. As an example there was the third exercise where we should build a tree data structure with recursive traversal. 

In the example you can see the constructor that initialize the priority queue an hands the two lowest values over to the *einfügen* methode. 

![image_6](https://db3pap003files.storage.live.com/y4mhJntkw5PxLAacH3AuOTn4510o4-20bmHU0AcGzTxD94iEND1SVdvID5wwD4wGPR3m3uhDYZNWQPtZkqR57Z_8Bt86NcmImOAQ6VCbp9IrNnTtevTKYpQgaPuiO7wsWl4VNj-ph2a1ECubwi_M4py5AvzgITZkcqYO6oUPcoD0Y4cAiiiCVJi9BiOO6uS-_YR?width=1466&height=624&cropmode=none)

The *einfügen* methode decides according to the different probabilities of the transferred elements whether one has to 'go' to the left or to the right. Finally, the 'parent' element is added to the PriorityQueue. The 'parent' element is 'above' element1 and element2.

![image_7](https://db3pap003files.storage.live.com/y4mlmjD9TCCELt5a_a0qysDRuD_64Y6cW4YtW_8dBYS2UCqzEHabrwp-en4s5Tj4MXb19ukV36UF8rH1LO6uGBQDXpnwTkS-rys1DkSikyIWZhHS9ShOyyXlaMUEDD6keQ1BbyON4Y_NTehJ9lvQVYwqeZHaHWgtdsum3sAqzl8T98yBs9QFX-dW6kohrBjhHYF?width=2656&height=978&cropmode=none)

Beside the weekly tasks the exam of the second semester was to create a 4 wins game with javafx in the mvc design pattern and a minimax algorithm. 
As an example you can see the minimax algorithm, which receives the recursion depth, the current player and the current playing field. It then evaluates the calculated results.

![image_8](https://db3pap003files.storage.live.com/y4mT0goZxcLcAzzTnuznbi305iaHr_wlMG7LhPqRjUZt2DYnuIhj8B7HDzxUNyprnWOEDFf-qp7buoE6Ou-mQ23lobOMHIRMNGsyMjN3yB49bPNBt7eQEPmwGPkb7vk9Cu4VVAdj1kb-QmHRCL1NbmV5mJuIrll_8F1CYM3P5nB5gZoZmZxPFukHtB41ca-RKW-?width=1868&height=1598&cropmode=none)

###### Three.js ######

For the submission in the computer graphics class, we should create a path that carries a ball downwards. This marble run should be created with Three.js. The first thing to do was to define the function with Nurbs Curve.

![image_10](https://db3pap003files.storage.live.com/y4mLwJRYR5eYOpxWK0xAqmp-E9pBhutg6A6YqO7Q87Jl_OpJ5XVFDzEKnfqMZG8Fc1kpIwzeYcXnza_Sw9PFfd8hCwGPmZXsr1f6LwG4WR3KkUf8I8ljJqbaIfLr5VkUry1rMTUt_qWIPVEoGmB9p1LrMWzAAafy4XirrMwTxcwW_cTKjVRwpQUFfiYVY1NvVrq?width=1380&height=1412&cropmode=none)

Then the marble is created and the movement is determined based on the function. In addition, the light was defined and the movement was initialized.

![image_10](https://db3pap003files.storage.live.com/y4mYmHE3kKF0ZiC3CRZ2A-mA5Q21ykpaftG9yLjZdxE2XMe_SR3WCSCzxAxCLcDItrtH7A2cCzZV1vZLeSHZDUc_yRaTbffLQpflTlEwWiOfKg1IScmkBMIvIDfq6eJxi1be0UCa_5j803IJ8eNUPipjENU5HvJHh5Qghnsu9YkSUNae-55rNvEHL7ovlBqYMTk?width=1688&height=742&cropmode=none)

###### HTML, CSS and JavaScript  ######

The second website we had to create was created by me in collaboration with a local startup (FormFux). Here it was most important to the founders that the images are dynamically animated with the scrolling. For this I used Lottie files and the renderer from the Lottie documentation. Unfortunately, the startup dissolved at the end of 2020, which meant that the website was never implemented. In addition, I used the Lottie animation in other areas as well. The example shows the one animation as used for the hamburger menu. 

![image_11](https://db3pap003files.storage.live.com/y4miw3EcCpUyeFt0tiEiSZWtjEOGj8OzPGEC3UKGEW6RsDwTrBzVTdXaEfxIb0m5BCY61SDw7epAMr7z5_8PpYKTsu2fBqPV_3RohvkkGitORZYcECAmgoyc9tiewaLsVmt8QA2bKr-xNpacm55Jhmvez0zzb4bCIa2mOdT54fKEcfaLNaWcaUAT5rSkROZDrFQ?width=898&height=1542&cropmode=none)

The website was also designed to be responsive. For this, media queries were used in the CSS, which were tailored to different display resolutions. 

![image_12](https://db3pap003files.storage.live.com/y4mOaODnK15602aYF6QwLvqVo59ofwVff5ZUydBlMdHI5LO5bmWLmz8zd8MifGPyquh7GjLampznEXOHFk7ciLnUTikp-x7FHqYWQUJ3x1EfOvZkBZwELgl8q1KJrTorPCZgxOlQ3H7mKTv-s6Rfl3ZE-LbWVyTzual4jCSk777JWhHd-4Guj8nwomgSVdHTOAB?width=978&height=840&cropmode=none)

###### PHP, HTML, CSS and JavaScript  ######

The last term paper in the 2nd semester was primarily concerned with the dynamic creation of websites through PHP. For this an online store was created, which (similar to Amazon) can load a number of products from an SQL database. Additionally it was possible to categorize the products with different filters. The first picture shows the connection of the database. Here the function has the possibility to load special articles from the database (attachment of the index).

![image_13](https://db3pap003files.storage.live.com/y4mdyxKUzvdPM6-1VCyE7rbhmWBQA9iEkCDYWEM8wboCGtECuof1gxUSGPZjKxEepx_gMRJbjiFk_rijLuFXria7YJtK5ObqS55aYlfZT38p8-Vpz8HHJkE5o2MQxQsHe8Je6tn5NkDMrKrNGuQ0xyKQTK6WPhwgNvd_mj5kz9yNecSQTRw3N6XDPtwf9AB9Qci?width=2082&height=1306&cropmode=none)

The second figure shows the dynamic creation of the filters

![image_14](https://db3pap003files.storage.live.com/y4mhtdB5uQSG6aHgU1SjkK-T4qIAR8o23bIIbpWj0KmA5jpLgIxZ8b5bnJ8y3m_SCS3JMw9v6nHvHppbgb1MRe7YyeW2uJtjz6hyX1JSucFS8HEttFIJQkHVio2n6FO-M-Xr5h8q8tpkZ9_rmlyA7BHqCwWvZE_4rHJPbXq7Bj0EtftIiiOaJTifq8oP038iC-J?width=1704&height=1476&cropmode=none)

## 3. Semester ##

###### Java ######

As with previous semesters, we had to solve and turn in an assignment each week. As with previous semesters, we had to solve and turn in an assignment each week. However, the tasks were increasingly focused on network programming with different clients. In this example, we had to create a chat program that is managed by a server. The messages appear on all devices at the same time. The first picture shows a method from the server, which creates the socket and stores all information from the client.

![image_15](https://db3pap003files.storage.live.com/y4mshi4eWMWIM8aBs0x13zJIhHvMjXo5U46oiKhX9DfMihoFXtR2sRDf5pSq1RgHD7J-buNz8ZjfDeTuckqwBlu3klRpWoZKlmn51EoL_Rvy1PfeHshRqH0FvUxLo4nvhbynPe0WA5FGb2FReEFkv9FM6eo7cXXS4CWyspalTx8KOd1gpAaNeE-gL2VJoxPhQIX?width=1610&height=576&cropmode=none)

The second image shows the client. The two methods establish the connection to the server and send the message. 

![image_16](https://db3pap003files.storage.live.com/y4mxtlRREtuVtqdPFeHZNw87LHW8Y57gDoG7ZRDVaHQUW16O21q57Mcv-qDi76LcAV_NBiGMD73n21HFZFHc1BZvQlSm68LzcZyJo6dir30gJDEmr0edFsGNzmaO7rA57JCESEZsD67X3gPbv0T1QUjQ5S33T9-eTY8Pl2CgRHQHJbI3_OcFrhBxK15CuJXT7eo?width=1560&height=1228&cropmode=none)

The term paper also included network programming. Here a music streaming service should be created, which has the data on a SQL database. The connection of the database was done via a singleton design pattern. 

![image_17](https://db3pap003files.storage.live.com/y4mc4lWUSRfTqRbFZ1_Yb6ejbigwE3vCGM1YADCc6MX4LJZ_NqVMigHd0LDOrpp3MG9u7ZQf_kV8JDhw5v4NDKV9XL3CLKO32JZ9VTwAKXk2Fu-OpZMmRnrrXG9b0_RzJAVUJU5zFxh0qaOyxJPJmt4mg05DMn1Qlkc10JaJkfjoFGiDndSxd7-lTauaAOTPWwe?width=1888&height=1600&cropmode=none)

For the application different artists with information had to be created as well as the music, which could be played by the client. The server was a glassfish-server, which was controlled via the Rest-API.

![image_18](https://db3pap003files.storage.live.com/y4m7x2n-yWvOEwPglOPVzqdFE3FgPG-UVpc5cWa_rnFt8CNozpvSCzS_X8MPHmW8m-oV5yjwp_lngMUEanfThoYTQkYwIzZQfL8lPmRTQDhmAF_ZpklH9koBIOvNOw7xYS-Ho_EjHcQmc2aRB6UnKj5eRiDB9Jf7ha6Cux93WljJF-FMlSVBRCJACWfm-M4WaiY?width=1824&height=1054&cropmode=none)

![image_19](https://db3pap003files.storage.live.com/y4mG0VxTdx5C5uJOiUkE0UTURU9X4_viafUaYMP7Vr5ziu6TkyTFhyMIBykO7lHsA0M4DL8oL-odjX0mjK8bpt0U6b5A3xLKvc8JBm_pKV2TpJXjyj71nDM9FowUO9f2ov1uvds-dXyri3RHQn0AUiAX7pXX2KoizZo00-FA4jeEcrLTYSBlqUrjb8wzADIWe1H?width=1386&height=1188&cropmode=none)

The data exchange took place via the JSON format. 

![image_20](https://db3pap003files.storage.live.com/y4mNoBVzUNpWQ_RPcnExqTDMpbd7kaICHwzlJdcFZgWJW7fvvNv-sMmgjo5JxGT_Mlu0vJIPnuwmos7I5-_873gMNYX6_ttciMmWE1Ck_f_mtsxYl_t7aQMf7nV6bEES8jvfyrCva5n9uCzluPvX_TpNwiA9jc3l599ZvhD_vtzPeGml4EsmyaWivcPtsHJkmZp?width=1812&height=1204&cropmode=none)

## 4. Semester ##

###### Android ######

In the fourth semester, the focus shifted to Android development. In addition, there were no weekly submissions. The homework consisted of developing an Android app that allows a fictitious restaurant to digitally store its guests (name, table number, etc.). Additionally, the customer should be able to customize the order (the choice of ingredients). The whole thing was created locally, without SQL database. Nevertheless, the GUI should dynamically adapt to different numbers of ingredients. For this purpose, a separate ListView was created, which was addressed by adding an adapter.

![image_21](https://db3pap003files.storage.live.com/y4mEr4-t1aI5tcFiriRnRlW16xT6mnbruZR2uK9PycupyJ68l3QBBu6ullZx1qK3BShxkA5kIy8TJthipAUFPMQ2e5SWDv_avfX4jltMnfxSspDu2G9eUA1wnAfxlulOs8sAdUBbIuTbpQMudtj6rOnDw8ORiS9hIydinc_TpClV1Zd8BN3qCiHX9uLI_iaGoCO?width=2216&height=1158&cropmode=none)

The ListView could then write all data into the defined XML file.

![image_22](https://db3pap003files.storage.live.com/y4mJmWLQXITuGxouPIJymO8j-nHbdJvhs4fWH7fzMxZ6jp-e6lUwSbZGEQ0cPYnMcvk3hJXHEvHPuQT8VbDViz1elseaboblLvROFl0VdysFImJh0HksQebyxUMfsi1mZLNUBKmgbxfmVOvIyCuDcYwoMhnMpyZaAyho2M5iWt0CRlU9IgkBfMMDpMMO2lgdi0I?width=1758&height=1372&cropmode=none)

###### C# ######

With Unity, the fourth semester also included familiarization with C#. A 3D game was developed in which the user can move a character through a world. The picture shows the development of the motion control and the camera control. 

![image_23](https://db3pap003files.storage.live.com/y4mVbgUfFuoFQCyHuivvxCUfEhuVVXnsvUl2sgeW0ic2pDOBsItSFcro1ONKol4w0P9bz5rFLUoVmQhcMPnxLHU7um9O7MbN1KSTHNiOSIVXHjgRawa2kfEsfmKTrTcwXCOEe0yq8Qk4ldnrnIfapNztVk61X5EPhqHVL5d8JdNTX1VS7oauKW4fIZTrKSDE-sL?width=1662&height=1298&cropmode=none)

![image_24](https://db3pap003files.storage.live.com/y4mHsoo3lBI-MG8pUQ_o-r9Y-44FsHGVA2ZipzddGix_e3NOn9oiFjBYapEsGFlsl7Zmi7-81MhPH6HOyE2oGxFjRjO8IE9VtVmf-wRHwp3L_dq1wioGHy60NZCtmQTzdIr_7HKOiThmDTdVAnQu_FA8C1C9XF5BBNBk0OLqHUHqnl_qJt8EU25OEwoD0djFtZZ?width=990&height=1636&cropmode=none)

## Repository ##

If you are interested in specific exams, I can send you an invitation for the repository. 
