### Автодетекченый форк репозитория

<img width="1094" height="436" alt="image" src="https://github.com/user-attachments/assets/d094e5c8-6f7d-4c00-9844-7188881b07c7" />

### Запущенный проект

<img width="810" height="184" alt="image" src="https://github.com/user-attachments/assets/b9296b39-0010-4d65-ba9a-98b364645cda" />


### Добавленный функционал

## В классе Welcomer реализован новый метод getHunterReply():

    public String getHunterReply() {
      return "The hunter is hiding somewhere. It should be the pheasant.";
      }
      
## Добавленный тест

  	@Test
      public void testGetHunterReplyContainsHunter() {
      String reply = welcomer.getHunterReply();
      assertThat(reply, containsString("hunter"));
	  }
