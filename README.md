# Titanic_Disaster
 Titanic - Machine Learning from Disaster

# Command:
# Image Build: 
docker build -t titanic_disaster_img .

# Container Build:
docker run --name titanic_disaster_cont -v D:\Projects\Titanic_Disaster:/analytics -w /analytics -p 8888:8888 titanic_disaster_img