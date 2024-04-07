# XSS in WonderCMS 3.4.3 (HOME PAGE)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz.

**Description:** Cross-site scripting (XSS) vulnerability in the HOME Page section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into all fields.

## PoC
### HOME Page
1. Enter to HOME page and in any parameter set the payload:

![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/8af7919b-a0c9-4be8-b5c5-74246daa5d38)
![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/c4987c0d-5757-4ff2-a59b-99e2494d2e43)

or

![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/2f473c75-41c9-46cf-b2da-9ba12933a3c3)
![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/55698bb3-f6a4-4f32-a88a-a2c9bcc6e6c6)

or

![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/2f473c75-41c9-46cf-b2da-9ba12933a3c3)
![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/762aab74-70c6-4f41-8222-b37cd19479af)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/7958efaf-d767-4926-9cb8-9ab19f911c20)
![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/f4ca5246-22ae-4d97-a9af-211c88af6e84)

or

![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/619a7b1d-48f0-4ec5-a977-ecee570b6304)
![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/c1463981-6942-407b-a662-13850e0c22e4)

or

![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/40d97ca8-b334-4af3-bb47-c17c5b849fd7)
![image](https://github.com/adiapera/xss_home_page_wondercms_3.4.3/assets/165512291/84ffa03d-7584-4f2b-a42e-54cceabefac1)



