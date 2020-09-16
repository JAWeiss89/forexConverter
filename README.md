# Forex Converter
Foreign currency converter app built using python and flask. No JS. Uses forex-python to retrieve latest exchange rates. 
<img width=20% src="https://lh3.googleusercontent.com/8ESR7-vH61b03mH_o0dtoJlIH8Tk8XpF-t2LoXH26l4ue5bJm6GsBd9fapHZCxjcVKE3hQ25y2f4J27r8JnyqPiwfwDELwv8kk1vfec2nTdocibdUeXacWkJNou25c9xXdCU8OARsnFrsOokV-RY84jt6ecjigFxjNBUoTWSBwjqz0tLTMjwpif43dAvaeEyr3fkGVFfph9OamOIOkLe5xmCkofylCivNOkOjiYmDrTHLjBy35QM7zLPfagylwkRHPw7X-lZB8ykaq0K42V9Ivzb_CyaJjhCLeBhRmULr1HYfTS4miYy2DKDrgvxeH6de0OTV8Tq8iCBDny6msEQa4IghWk0fBCgYDBOVlIHnyFpqapOEXLhzM_elQvJh0NywmpoTssmfvLKSSBdyVqmitnLk9-DbtZDWEiRCmTaVPH3A54ljX6o3t2TVkPBwuq0xmUAWO7IN5u9S0slxDVY0AbTl4X43jp6ocLBBLWjq9oihraZWGJWzEzKc88_5sobDdbzqk25CqwLQ5X0P_MlgTYUkTAB14226seEiArRRdjSF1lwirSsH9aOzDu61eGuOAsU2uHb38q6etxnUoS8uB8KZJkFPCmIYWK8p8otB7BQqyq1JaWdMr5f30GhNoGzoauDIGqHxPMUkctx3Thr0wtSczV4cQKpe7mNkIYHhqvVo5GHeAWMhU9ky3I9=w834-h1199-no?authuser=0">


Ideally this application would be made wish AJAX to create a better UX but I sought out to create a web app without a client-side script file. Although it was possible to create the application without the script file, page redirects were necessary without the AJAX functionality.

## technology used
* Open source [forex-python](https://github.com/MicroPyramid/forex-python) was used to retrieve latest exchange rates.
* Flask (lightweight python framework) was used to handle routes and make server-side API calls using the `requests` dependency. 
