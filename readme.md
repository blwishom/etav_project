# Welcome to the Extract Transform Analyze and Visualize Readme!

### This project is coded in a Jupyter Notebook in which each kernal can be ran individually after the first 2 kernals are ran in sequential order. The first kernal imports the necessary technologies for the project while the second kernal reads the data used for the project. The photographs below exemplify the results of each kernal.

#### Run the kernals by hovering over each kernal then clicking the play button in the top left corner. Once a green check displays in the bottom left corner, the kernal has completed running. You can also run all kernals simultaneously in sequential order by clicking the "Run All" play button at the top of the file.
![Screenshot (472)](https://user-images.githubusercontent.com/79879124/236651905-8bb13b5d-c1e5-4964-877e-99faee3cadc0.png)

1. These 2 kernals import the necessary technologies for the project and read the data used for the project:
![Screenshot (452)](https://user-images.githubusercontent.com/79879124/236651062-f5783c7f-39c8-43c4-a5c3-208e8dde1251.png)

2. This kernal extracts specific data from the database while renaming the columns and also filling in NaN values with logical text and creates a dataframe to be used throughout the rest of the project:
![Screenshot (453)](https://user-images.githubusercontent.com/79879124/236651076-3b780596-75bd-4220-9cf7-e68a625e9446.png)

3. This kernal combines 2 columns of data from the dataframe and displays the data in a 2-D visual:
![Screenshot (454)](https://user-images.githubusercontent.com/79879124/236651078-648f42be-3f06-4838-ae22-615be1aefcda.png)

4. This kernal removes rows with no data from the previous kernal in order for the 2-D visual to only display rows that consist of data and also orders the usCasesPerYear column in descending order from highest amount of cases to lowest:
![Screenshot (455)](https://user-images.githubusercontent.com/79879124/236651081-40ae6fc4-77f6-4049-b5bd-2c29630ff7e2.png)

5. This kernal groups the US Cases Per Year by grabbing the highest amount of cases(max), lowest amount of cases (min) and the average between the highest and lowest amounts (avg):
![Screenshot (462)](https://user-images.githubusercontent.com/79879124/236651122-7e43afa6-db80-47bf-8759-472e16a94162.png)

6. This kernal grabs the total amount of each type of cancer and displays the cancer type in order of greatest amount of cases to least:
![Screenshot (457)](https://user-images.githubusercontent.com/79879124/236651135-488dbc82-65dd-46a7-b9d4-687ee37e24ff.png)

7. This kernal grabs the top 5 types of cancers and displays them in a bar graph:
![Screenshot (458)](https://user-images.githubusercontent.com/79879124/236651143-e23b6670-3dcb-4c5d-83ae-f364da9d3d54.png)

8. This kernal grabs the top 5 types of cancers and displays them in a pie chart:
![Screenshot (459)](https://user-images.githubusercontent.com/79879124/236651146-e1389d0b-be22-4905-b2ce-ad1b6dd99758.png)

9. This kernal grabs the top 5 types of cancers and displays them in a scatter plot:
![Screenshot (461)](https://user-images.githubusercontent.com/79879124/236651150-47ff0c5e-73e2-449b-be78-f79cbe66bc34.png)
