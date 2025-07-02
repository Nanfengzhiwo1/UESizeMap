# SizeMap
<img width="1894" alt="企业微信截图_17514237608886" src="https://github.com/user-attachments/assets/06be1f2a-f9cc-4201-bc42-160abd75d441" />

### Dependencies to Display
**Game**:Visualize all hard references held by the current asset
### Size to Display
**Memory Size**:Display the memory occupied by the referenced assets

## Check hard ref in Size Map
_if add a hard ref in BP_MyGameMode ,it will appear in Size Map,soft ref is not._
![image](https://github.com/user-attachments/assets/ff894743-da13-482f-99c5-11259223fd9b)
![image](https://github.com/user-attachments/assets/e1217a95-4b91-4cd5-9233-bcfdf0badd7f)

## Reduce the memory size
_Change hard reference to soft reference_
_Optimize Textures,for example Mip Gen Settings:FromTextureGroup->NoMipmaps（This is just an example, it is not necessary to do this）_
![image](https://github.com/user-attachments/assets/8e524681-8fea-4680-9643-349154c3cd23)
