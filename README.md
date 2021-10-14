# CatPaw_OSINT
This project is designed to identify the approximate place of life of a certain person based on data from the social network Instagram. The program finds general information about the object, and also uses the geolocation of photographs and the most frequently visited place of a person. As a result, a map with a geo tag.
>To use these programs, you need python on your system.
# Download

```console
git clone https://github.com/sakyra01/CatPaw_OSINT.git

```

# Installation and work
1. Install the required packages from requrements:
```console
pip3 install -r requirements.txt
```
2. How to use:
> At first you can use 2 types of keys
> 
> * -u, --user - add here target instagram account
> 
> * -l, --location - just write after -u key if you want to see location
 
```console
python3 instagram.py -u <your target's account name> -l 
```
![InkedScreenshot from 2021-09-07 18-34-43_LI](https://user-images.githubusercontent.com/57565730/132383324-8afb4304-b29c-4ab7-925f-a32eb2eb4752.jpg)
![Screenshot from 2021-09-07 19-17-15](https://user-images.githubusercontent.com/57565730/132382287-3f8754b1-acc5-4339-bff2-311acce61f66.png)
3. If you have some troubles just write:
 ```console
python3 instagram.py -h 
```
![Screenshot from 2021-09-07 19-17-50](https://user-images.githubusercontent.com/57565730/132382431-7f8da29d-1c43-4a10-a2b1-a689ff425ac8.png)
