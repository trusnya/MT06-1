# Activities  

## 1.GET/api/v1/Activities  
- HTTP-метод: GET  
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities  
- Заголовки запроса: accept: text/plan; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0  
- Статус-код ответа: 200 Success
- Тело ответа:  
{  
"id": 1,  
"title": "Activity 1",   
"dueDate": "2023-09-10T11:37:53.2042626+00:00",    
"completed": false    
},   
{    
"id": 2,    
"title": "Activity 2",    
"dueDate": "2023-09-10T12:37:53.2042648+00:00",    
"completed": true      
},    
{  
"id": 3,  
"title": "Activity 3",  
"dueDate": "2023-09-10T13:37:53.2042651+00:00",  
"completed": false  
},  
{  
"id": 4,  
"title": "Activity 4",  
"dueDate": "2023-09-10T14:37:53.2042653+00:00",  
"completed": true  
},  
{  
"id": 5,  
"title": "Activity 5",  
"dueDate": "2023-09-10T15:37:53.2042656+00:00",  
"completed": false  
},  
{  
"id": 6,  
"title": "Activity 6",  
"dueDate": "2023-09-10T16:37:53.2042661+00:00",  
"completed": true  
},  
{  
"id": 7,  
"title": "Activity 7",  
"dueDate": "2023-09-10T17:37:53.2042664+00:00",  
"completed": false  
{  
"id": 8,  
"title": "Activity 8",  
"dueDate": "2023-09-10T18:37:53.2042666+00:00",  
"completed": true  
},  
{  
"id": 9,  
"title": "Activity 9",  
"dueDate": "2023-09-10T19:37:53.2042669+00:00",  
"completed": false  
},  
{  
"id": 10,  
"title": "Activity 10",  
"dueDate": "2023-09-10T20:37:53.2042675+00:00",  
"completed": true  
}  

## 2.POST/api/v1/Activities    
- HTTP-метод: POST    
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities    
- Заголовки запроса: Content-Type: application/*+json; v=1.0, Content-Type: application/json; v=1.0, accept: text/json; v=1.0,    `  
- Тело запроса:       
{  
"id": 0,  
"title": "string",  
"dueDate": "2023-09-10T10:51:50.913Z",  
"completed": true  
}  
- Статус-код ответа: 200 Success  
- Тело ответа:  
{  
"id": 0,  
"title": "string",  
"dueDate": "2023-09-10T10:51:50.913Z",  
"completed": true  
}`    

##3.GET/api​/v1​/Activities​/{id}    
- HTTP-метод: GET   
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/5  
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0  
- Статус-код ответа: 200 Success   
- Тело ответа:   
`{  
  "id": 5,  
  "title": "Activity 5",  
  "dueDate": "2023-09-10T22:00:23.4569533+00:00",  
  "completed": false  
}`  

##4.PUT/api​/v1​/Activities​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/5
- Заголовки запроса: accept: text/plain; v=1.0", Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
`{
  "id": 0,
  "title": "string",
  "dueDate": "2023-09-10T17:01:07.554Z",
  "completed": true
}`

- Статус-код ответа: 200 Success
- Тело ответа:
`{
  "id": 0,
  "title": "string",
  "dueDate": "2023-09-10T17:01:07.554Z",
  "completed": true
}`  

##5.DELETE/api​/v1​/Activities​/{id}
- HTTP-метод: DELETE
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/5
- Заголовки запроса: accept: */* 
- Статус-код ответа: 200 Success

#Authors

##6.GET/api​/v1​/Authors
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0
- Статус-код ответа: 200 Success
- Тело ответа:
[
  {
    "id": 1,
    "idBook": 1,
    "firstName": "First Name 1",
    "lastName": "Last Name 1"
  },
  {
    "id": 2,
    "idBook": 1,
    "firstName": "First Name 2",
    "lastName": "Last Name 2"
  },
  {
    "id": 3,
    "idBook": 1,
    "firstName": "First Name 3",
    "lastName": "Last Name 3"
  },
  {
    "id": 4,
    "idBook": 1,
    "firstName": "First Name 4",
    "lastName": "Last Name 4"
  },
  {
    "id": 5,
    "idBook": 2,
    "firstName": "First Name 5",
    "lastName": "Last Name 5"
  },
  {
    "id": 6,
    "idBook": 2,
    "firstName": "First Name 6",
    "lastName": "Last Name 6"
  },
  {
    "id": 7,
    "idBook": 3,
    "firstName": "First Name 7",
    "lastName": "Last Name 7"
  },
  {
    "id": 8,
    "idBook": 3,
    "firstName": "First Name 8",
    "lastName": "Last Name 8"
  },
  {
    "id": 9,
    "idBook": 3,
    "firstName": "First Name 9",
    "lastName": "Last Name 9"
  },
  {
    "id": 10,
    "idBook": 3,
    "firstName": "First Name 10",
    "lastName": "Last Name 10"
  }
]

##7.POST/api​/v1​/Authors
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

##8.GET/api​/v1​/Authors​/authors​/books​/{idBook}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/5
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 200 Success
- Тело ответа:
[
  {
    "id": 15,
    "idBook": 5,
    "firstName": "First Name 15",
    "lastName": "Last Name 15"
  },
  {
    "id": 16,
    "idBook": 5,
    "firstName": "First Name 16",
    "lastName": "Last Name 16"
  },
  {
    "id": 17,
    "idBook": 5,
    "firstName": "First Name 17",
    "lastName": "Last Name 17"
  }
]

##9.GET/api​/v1​/Authors​/{id}
- HTTP-метод: GET 
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/5
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 5,
  "idBook": 2,
  "firstName": "First Name 5",
  "lastName": "Last Name 5"
}

##10.PUT/api​/v1​/Authors​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/5
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, accept: text/json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}

##11.DELETE/api​/v1​/Authors​/{id}
- HTTP-метод: DELETE
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/5
- Заголовки запроса: accept: */*
- Статус-код ответа: 200 Success

#Books

##12.GET/api​/v1​/Books
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0 
- Статус-код ответа: 200 Success
- Тело ответа:
[
  {
    "id": 1,
    "title": "Book 1",
    "description": "Sit gubergren et. Elitr et gubergren clita velit consetetur tempor et tempor sadipscing diam. Velit vel quis vero vel euismod eos dolore lorem possim et sed sit. Tation consequat aliquyam ut vulputate justo autem ipsum sed amet labore vel sed illum gubergren elitr et. Rebum eos qui nostrud sit amet aliquyam zzril ut nonumy ea rebum erat sanctus ipsum eos amet sea amet. Sed no elitr diam justo erat soluta sed at dolor adipiscing stet accusam vel erat sanctus ea magna. Ut vel ipsum sadipscing diam. Rebum vulputate et vero. Ut sed quis ea erat amet. Nostrud lorem volutpat sed lorem voluptua vel labore eirmod aliquam invidunt lorem sed nibh.\n",
    "pageCount": 100,
    "excerpt": "At ipsum kasd eum nisl lobortis nonumy lorem vulputate velit takimata justo dolor et sed elitr. Sadipscing iriure facilisi nulla magna stet justo consequat sadipscing sit dolor kasd et dolor elitr sadipscing magna ut. Nonummy augue volutpat eos lorem sed zzril eleifend no id. Dolor diam facilisis. Vulputate eirmod erat feugiat duo blandit nostrud ipsum facilisis rebum diam vel.\nAmet iriure nonumy enim. Dolore lorem amet diam dolore tincidunt consectetuer sit esse ut feugait eirmod adipiscing. Ut ut dolor sed option at nonumy zzril ipsum.\nSed aliquam eros accusam kasd diam dolor invidunt stet ut sit ea euismod. Ipsum takimata et ut illum labore et diam consequat duo amet praesent dolore. In sed ut facilisis sit zzril ea kasd elit at vero placerat qui magna eu ut at. Ex tempor sed amet feugiat velit dolores dolor elitr diam qui. Accusam nulla dignissim invidunt molestie aliquyam sit lorem at eirmod zzril takimata diam et amet elitr aliquyam et. Dolor tempor ea placerat consectetuer amet soluta sanctus assum sanctus consectetuer nulla vero aliquip magna aliquam. Sea eos tempor veniam eirmod et. Eum invidunt nam at clita stet aliquip duo. Ut dolor stet diam consequat elit congue sit tempor nulla et facilisis et sed.\nAt labore no et aliquip justo sea et elitr invidunt aliquip. Molestie ipsum et dignissim dolores iriure tation justo et lorem. Et clita at rebum lorem id zzril ipsum et dolores sadipscing ea eu eleifend feugiat. Ipsum ea nulla amet sed rebum tincidunt. Eum vel amet vero exerci ipsum justo nulla eirmod. Erat ex invidunt cum elitr et soluta. Accusam et enim. Lorem nibh dolor nonumy stet nonumy kasd delenit at et feugiat gubergren feugiat et lorem. Tempor sadipscing dolore justo esse no ipsum et ipsum tempor. Sed elitr ipsum dolor invidunt dolor vero sadipscing no et. Ut et nostrud duo nonummy sea eos zzril vero accusam sadipscing velit.\nEos velit placerat et ipsum sea sit ea tincidunt sed et et possim dolor dolor euismod nisl sit. Dolor invidunt eu consequat et et sanctus. Est placerat dolor eos est nonumy vulputate duo invidunt dolores velit congue sit sit exerci sit rebum. Elitr lorem magna. Velit no feugiat. Accusam kasd sit sit ipsum dolore amet dolor magna dolor duo. Ut sadipscing elitr rebum.\n",
    "publishDate": "2023-09-09T17:32:42.9544554+00:00"
  }
]

##13.POST/api​/v1​/Books
- HTTP-метод: POST 
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books 
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса:
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-09-10T17:35:29.892Z"
} 
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-09-10T17:35:29.892Z"
}

##14.GET/api​/v1​/Books​/{id}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/5
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 5,
  "title": "Book 5",
  "description": "Nostrud aliquyam amet duo dolores eos aliquip ut et at esse lorem takimata. Et tempor lorem aliquyam consequat iusto dolores diam labore ut amet dignissim dolor magna amet. Ea euismod at sit sadipscing ut tempor dolore erat takimata esse consetetur. Et ea rebum et diam qui velit delenit mazim stet hendrerit ipsum diam magna eirmod dolor dolor erat aliquip. Ipsum accusam et gubergren suscipit invidunt accusam amet consequat vero vulputate justo et doming elitr nonumy nulla. Nihil assum et dolor dolores amet rebum magna sed soluta esse sanctus vero dolor accusam et. Vero nulla vero dolor. Esse sadipscing elitr.\n",
  "pageCount": 500,
  "excerpt": "Clita dolore et. Congue dolore diam voluptua et dolor. Duo nisl amet amet dolor. Sed ut diam ut sanctus et gubergren diam sea enim aliquip vero vel kasd.\nLorem ea takimata luptatum diam est dolores est sadipscing sed vel magna nibh congue. Elit no diam lorem ut luptatum amet nobis stet dolore vero dolore delenit magna amet clita duis stet sit. Esse et nonumy dolore placerat clita et sanctus erat. Erat quis dolor ipsum diam eirmod erat. Tempor sit dolores labore amet duo tincidunt at diam sed eum. Feugiat option erat adipiscing in vero diam sit justo dolore ea lorem nonumy consequat. Erat gubergren et dolore dolore at.\nDuo dolor sed consetetur tempor labore ea nulla sit wisi elitr est clita dolor dolore aliquyam. Ad odio tincidunt sadipscing no invidunt ipsum et dolor. Consequat et aliquip magna. Dolores iriure nonumy lorem ipsum esse sit. Liber diam sed illum et qui sanctus sed gubergren. Ipsum takimata ex sea ut at et. Et eos est. Aliquyam et diam ipsum sit. No iriure nihil dolor voluptua sanctus diam eirmod sanctus ut nulla tempor ipsum labore rebum lorem. Justo ut amet voluptua. Commodo elitr feugiat nisl. Elitr dolore vulputate voluptua quis. Exerci voluptua labore vero consetetur dolor stet et consectetuer sea et et eos. Facilisis diam diam diam rebum. Ut at praesent ea sed aliquip clita sea. Invidunt qui sed dolore ipsum lorem sed sit sit aliquyam gubergren feugait diam sit.\nIpsum sanctus blandit amet dolor qui vulputate in diam et in velit gubergren illum duo eos labore aliquyam. Praesent ut amet sed ullamcorper ipsum lobortis. Et ut mazim amet ex labore eum ut ad iriure clita dolor takimata at dolore. Accusam adipiscing iusto amet sit ex. Diam sit elitr. Accusam rebum et suscipit gubergren aliquyam feugiat nisl stet consetetur sit cum. Dolor vero dignissim consequat tincidunt erat sit at et lorem sanctus sed in sed elit ut labore gubergren lobortis. Lorem eros eirmod. Amet amet eu sit ut volutpat. Illum at sea vero erat sea et diam et sed. Sanctus erat labore et invidunt consetetur consetetur voluptua rebum diam nostrud et invidunt et dolor clita. Dolor eirmod dolores in augue et ipsum ipsum et. Nulla justo consequat accusam molestie sed enim voluptua kasd dolor voluptua stet vulputate stet nibh diam.\nAccusam dolor diam praesent eos facilisi et facer rebum et dolor stet. Iusto velit et dolores quis magna. Dolore lobortis et rebum. Et gubergren dolor stet. Et at exerci esse diam te tempor liber takimata clita nibh erat nonumy. Amet lorem qui ut erat praesent est consetetur autem lorem voluptua sadipscing ut elitr aliquyam gubergren. Dolores voluptua illum stet rebum tincidunt praesent exerci amet takimata sanctus sed sit adipiscing. Diam laoreet no. Zzril diam aliquyam euismod ipsum. Nulla aliquam ut sea est consequat magna diam amet volutpat dolor sed labore veniam erat. Elitr amet duo wisi diam accusam minim eirmod aliquyam mazim in velit et. Gubergren autem aliquip velit labore lorem sit lorem diam gubergren praesent ipsum eros. Ut stet amet. Diam tation odio eu nihil. Eros quis illum dolor dolor id dolor tincidunt duis te sanctus vero lorem.\n",
  "publishDate": "2023-09-05T17:39:02.086238+00:00"
}

##15.PUT/api​/v1​/Books​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/5
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-09-10T17:39:52.895Z"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-09-10T17:39:52.895Z"
}

##16.DELETE/api​/v1​/Books​/{id}
- HTTP-метод: DELETE
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/5
- Заголовки запроса: accept: */*
- Статус-код ответа: 200 Success

#CoverPhotos

##17.GET/api​/v1​/CoverPhotos
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 200 Success
- Тело ответа:
[
  {
    "id": 1,
    "idBook": 1,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 1&w=250&h=350"
  },
  {
    "id": 2,
    "idBook": 2,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 2&w=250&h=350"
  },
  {
    "id": 3,
    "idBook": 3,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 3&w=250&h=350"
  },
  {
    "id": 4,
    "idBook": 4,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 4&w=250&h=350"
  },
  {
    "id": 5,
    "idBook": 5,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 5&w=250&h=350"
  },
  {
    "id": 6,
    "idBook": 6,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 6&w=250&h=350"
  },
  {
    "id": 7,
    "idBook": 7,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 7&w=250&h=350"
  },
  {
    "id": 8,
    "idBook": 8,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 8&w=250&h=350"
  },
  {
    "id": 9,
    "idBook": 9,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 9&w=250&h=350"
  },
  {
    "id": 10,
    "idBook": 10,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 10&w=250&h=350"
  }
]

##18.POST/api​/v1​/CoverPhotos
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}

##19.GET/api​/v1​/CoverPhotos​/books​/covers​/{idBook}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/books/covers/5
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0 
- Статус-код ответа: 200 Success
- Тело ответа:
[
  {
    "id": 5,
    "idBook": 5,
    "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 5&w=250&h=350"
  }
]

##20.GET/api​/v1​/CoverPhotos​/{id}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/5
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 5,
  "idBook": 5,
  "url": "https://placeholdit.imgix.net/~text?txtsize=33&txt=Book 5&w=250&h=350"
}

##21.PUT/api​/v1​/CoverPhotos​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/5
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "idBook": 0,
  "url": "string"
}

##22.DELETE/api​/v1​/CoverPhotos​/{id}
- HTTP-метод: DELETE
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/5
- Заголовки запроса: accept: */*
- Статус-код ответа: 200 Success

#Users

##23.GET/api​/v1​/Users
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0 
- Статус-код ответа: 200 Success
- Тело ответа:
[
  {
    "id": 1,
    "userName": "User 1",
    "password": "Password1"
  },
  {
    "id": 2,
    "userName": "User 2",
    "password": "Password2"
  },
  {
    "id": 3,
    "userName": "User 3",
    "password": "Password3"
  },
  {
    "id": 4,
    "userName": "User 4",
    "password": "Password4"
  },
  {
    "id": 5,
    "userName": "User 5",
    "password": "Password5"
  },
  {
    "id": 6,
    "userName": "User 6",
    "password": "Password6"
  },
  {
    "id": 7,
    "userName": "User 7",
    "password": "Password7"
  },
  {
    "id": 8,
    "userName": "User 8",
    "password": "Password8"
  },
  {
    "id": 9,
    "userName": "User 9",
    "password": "Password9"
  },
  {
    "id": 10,
    "userName": "User 10",
    "password": "Password10"
  }
]

##24.POST/api​/v1​/Users
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "userName": "string",
  "password": "string"
}

##25.GET/api​/v1​/Users​/{id}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/5
- Заголовки запроса: accept: */*,  
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 5,
  "userName": "User 5",
  "password": "Password5"
}

##26.PUT/api​/v1​/Users​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/5
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "userName": "string",
  "password": "string"
}
- Статус-код ответа: 200 Success
- Тело ответа:
{
  "id": 0,
  "userName": "string",
  "password": "string"
}

##27.DELETE/api​/v1​/Users​/{id}
- HTTP-метод: DELETE
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/5
- Заголовки запроса: accept: */*
- Статус-код ответа: 200 Success  

#Activities  

##28.GET/api​/v1​/Activities​/{id}
- HTTP-метод: GET 
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/10000000
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 404 Error: Not Found 
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.4",
  "title": "Not Found",
  "status": 404,
  "traceId": "00-d734b37b27baf346bcc2b7179c16b9c1-b5f30f51ad7bc74e-00"
}  

##29.PUT/api​/v1​/Activities​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities/10000000000000
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-09-10T17:01:07.554Z",
  "completed": true
}
- Статус-код ответа: 400 Error: Bad Reques
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-ed9bcb1e42c83d4da6ea3d0cab78838a-d3b727f735f39b45-00",
  "errors": {
    "id": [
      "The value '10000000000000' is not valid."
    ]
  }
}

##30.POST/api​/v1​/Activities
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Activities
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "title": "string",
  "dueDate": "2023-09-10T10:51:50.913Z",
  "completed": true c
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-71b53624cd2fa745948bdf957337454c-80d9cf645fed084f-00",
  "errors": {
    "$": [
      "'c' is invalid after a value. Expected either ',', '}', or ']'. Path: $ | LineNumber: 4 | BytePositionInLine: 20."
    ]
  }
}

#Authors

##31.POST/api​/v1​/Authors
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, accept: text/json; v=1.0 
- Тело запроса: 
{
  "id": tr,
  "idBook": 0,
  "firstName": "string",
  "lastName": "string"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-0b911de2af963f4196b57433f9266c68-79103a0f1213f943-00",
  "errors": {
    "$.id": [
      "'tr,\n  \"idBook\": 0,\n  \"firstName\": \"string\",\n  \"lastName\": \"string\"\n}' is an invalid JSON literal. Expected the literal 'true'. Path: $.id | LineNumber: 1 | BytePositionInLine: 10."
    ]
  }
}

##32.POST/api​/v1​/Authors
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors
- Заголовки запроса: accept: text/json; v=1.0, accept: application/json; v=1.0, Content-Type: application/json; v=1.0,  
- Тело запроса: 
{
  "id": 10000000000000,
  "idBook": 1000000000000,
  "firstName": "string",
  "lastName": "string"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-da097893c5535d48bf7a4618ecf60119-ac1a97db82777946-00",
  "errors": {
    "$.id": [
      "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 0 | BytePositionInLine: 20."
    ]
  }
}

##33.GET/api​/v1​/Authors​/authors​/books​/{idBook}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/authors/books/10000000000000000
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Статус-код ответа: 400 Error: Bad Request
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-55301113c0eab9468479290c7481ecf5-cf38461400864745-00",
  "errors": {
    "idBook": [
      "The value '10000000000000000' is not valid."
    ]
  }
}

##34.PUT/api​/v1​/Authors​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Authors/1000000000
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0
- Тело запроса: 
{
  "id": 10000000000,
  "idBook": 1000000000000,
  "firstName": "string",
  "lastName": "string"
} 
- Статус-код ответа: 400 Error: Bad Request 
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-12326de07756c140be1c0a1453dfb40f-614f48ddcaf29947-00",
  "errors": {
    "$.id": [
      "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 0 | BytePositionInLine: 17."
    ]
  }
}

#Books

##35.POST/api​/v1​/Books
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": tr,
  "title": "string",
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-09-11T08:53:38.462Z"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-df4260438f759448a15d0c766d80a607-a403ddacd4042141-00",
  "errors": {
    "$.id": [
      "'tr,\n  \"title\": \"string\",\n  \"description\": \"string\",\n  \"pageCount\": 0,\n  \"excerpt\": \"string\",\n  \"publishDate\": \"2023-09-11T08:53:38.462Z\"\n}' is an invalid JSON literal. Expected the literal 'true'. Path: $.id | LineNumber: 1 | BytePositionInLine: 10."
    ]
  }
}

##36.PUT/api​/v1​/Books​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Books/10000000000
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "title":,
  "description": "string",
  "pageCount": 0,
  "excerpt": "string",
  "publishDate": "2023-09-11T08:59:46.810Z"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-41af845e7f3ac94896f880396f9efa10-c068f5bc9f37a140-00",
  "errors": {
    "id": [
      "The value '10000000000' is not valid."
    ],
    "$.title": [
      "',' is an invalid start of a value. Path: $.title | LineNumber: 2 | BytePositionInLine: 10."
    ]
  }
}

##37.POST/api​/v1​/CoverPhotos
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0
- Тело запроса: 
{
  "id": 0,
  "url": 
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-92a0f00d67b51e47b725c8bf02876c41-c5fac7712015b045-00",
  "errors": {
    "$.url": [
      "'}' is an invalid start of a value. Path: $.url | LineNumber: 3 | BytePositionInLine: 0."
    ]
  }
}

##38.GET/api​/v1​/CoverPhotos​/{id}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/1000000000000000
- Заголовки запроса: accept: text/plain; v=1.0, accept: application/json; v=1.0, accept: text/json; v=1.0 
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-938f27178f21cb4eb8a2fbe7d3186886-18157ab8f3b4ad43-00",
  "errors": {
    "id": [
      "The value '1000000000000000' is not valid."
    ]
  }
}

##39.PUT/api​/v1​/CoverPhotos​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/0
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0 
- Тело запроса: 
{
  "id": 9,
  "idBook": l,
  "url": "spring"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-b6131a9006c6294dabb80cb0eb2911ec-0bb38592c36a3740-00",
  "errors": {
    "$.idBook": [
      "'l' is an invalid start of a value. Path: $.idBook | LineNumber: 2 | BytePositionInLine: 12."
    ]
  }
}

##40.PUT/api​/v1​/CoverPhotos​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/CoverPhotos/100000000000000000000000
- Заголовки запроса: accept: text/plain; v=1.0, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0 
- Тело запроса: 
{
  "id": 0,
  "idBook": 100,
  "url": "spring"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-d5921ed534c6d148a7b047d300a61c79-a0ba8da0e887ac4a-00",
  "errors": {
    "id": [
      "The value '100000000000000000000000' is not valid."
    ]
  }
}

#Users

##41.POST/api​/v1​/Users
- HTTP-метод: POST
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0
- Тело запроса: 
{
  "id": 1000000000000,
  "userName": "string",
  "password": "string"
}
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-5e0a1ed02beeb1408afcefcf04362970-927dcc275dbc3f40-00",
  "errors": {
    "$.id": [
      "The JSON value could not be converted to System.Int32. Path: $.id | LineNumber: 0 | BytePositionInLine: 19."
    ]
  }
}

##42.GET/api​/v1​/Users​/{id}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/10000000000000
- Заголовки запроса: accept: */*,  
- Статус-код ответа: 400 Error: Bad Request 
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-7c2332a22fa2a0469d57187bec874c13-aa9b5da2b8de4d4c-00",
  "errors": {
    "id": [
      "The value '10000000000000' is not valid."
    ]
  }
}

##43.GET/api​/v1​/Users​/{id}
- HTTP-метод: GET
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/-5
- Заголовки запроса: accept: */* 
- Статус-код ответа: 404 Error: Not Found
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.4",
  "title": "Not Found",
  "status": 404,
  "traceId": "00-5aa492f9f3ac0844b2239c0a43366384-814f8f8575278642-00"
}

##44.PUT/api​/v1​/Users​/{id}
- HTTP-метод: PUT
- Полный URL запроса: https://fakerestapi.azurewebsites.net/api/v1/Users/10000000000000000000
- Заголовки запроса: accept: */*, Content-Type: application/json; v=1.0, Content-Type: text/json; v=1.0, Content-Type: application/*+json; v=1.0 
- Статус-код ответа: 400 Error: Bad Request
- Тело ответа:
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-9cea0b884ffe3749ba446e15925b398d-d9fdb578afec674d-00",
  "errors": {
    "id": [
      "The value '10000000000000000000' is not valid."
    ]
  }
}
