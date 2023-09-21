# Classification Problem

This is a supervised learning problem. I followed the workflow of [Kylie Ying](https://www.youtube.com/watch?v=i_LwzRVP7bg) from freecodecamp to solve this problem. 

## Dataset
The dataset is from [UCI Irvine machine Learning Repository](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope). In this **MAGIC** **Gamma** **Telescope** dataset, the target variable is a binary variable. 

### About Dataset
The high energy particles hitting Gamma telescope, and the pattern of light particles hitting the telescope are recorded. We can use properties of those patterns to predict what type of particle (gamma/ hadron) causes the radiation. The dataset contains 19020 observations and 11 features. The target variable is a binary variable. Following are the features of the dataset:
1. **fLength**: continuous # major axis of ellipse [mm]
2. **fWidth**: continuous # minor axis of ellipse [mm]
3. **fSize**: continuous # 10-log of sum of content of all pixels [in #phot]
4. **fConc**: continuous # ratio of sum of two highest pixels over fSize [ratio]
5. **fConc1**: continuous # ratio of highest pixel over fSize [ratio]
6. **fAsym**: continuous # distance from highest pixel to center, projected onto major axis [mm]
7. **fM3Long**: continuous # 3rd root of third moment along major axis [mm]
8. **fM3Trans**: continuous # 3rd root of third moment along minor axis [mm]
9. **fAlpha**: continuous # angle of major axis with vector to origin [deg]
10. **fDist**: continuous # distance from origin to center of ellipse [mm]
11. **class**: g,h # gamma (signal), hadron (background)

