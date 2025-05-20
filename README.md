## API

- ChatGPT:https://rapidapi.com/rphrp1985/api/chatgpt-42/playground/
apiendpoint_4945d7ba-fd20-47de-ac8b-1c137f52ae52
##

/API'ye istek atabilmemis için ınputun içerisindeki değeri almamız gerekir.

/Bu değeri alırken send butonuna tıkladığımızda alacağız.

-Inputun içerisindeki değeri kullanıcı profilin yanına eklememiz gerekir.

-Bunu gerçekleştirirken yeniden kullanabileceğimiz bir `createElement` fonksiyonu oluşturduk ve buna iki parametre gönderdik.Birinci parametre chat-containera eklemek istediğimiz html yapısıdır.İkinci parametre ise eklemek istediğimiz htmlin class ismidir.

-Kullanıcı veriyi girdikten sonra anımasyonu`showTypingAnimation`fonksiyonunu kullanarak ekrana bastık.Sonrasında da kullanıcının girdiği veriye göre `getChatResponse` fonksiyonu ile API'ye istek atmamız gerekir.

-İstek atarken asenkron işlem olduğu iic async  await ile bekledik.

-`getChatResponse` fonksiyonunu parametre olarak incomingChaTdİV'i gönderdik.Çünkü veritabanından gelen veriyi incomingChatDiv'in içerisinde bulunan typinganimation yerine aktaracağız.# chatGbt-Clone

Screen Gif
![Image](https://github.com/user-attachments/assets/007401aa-cce8-4f43-9f50-db4835d484d6)
