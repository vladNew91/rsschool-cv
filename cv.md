# Junior front-end developer



1. **Uladzislau, Nazarau**

2. *vladnew91@gmail.com, https://www.linkedin.com/in/uladzislau-nazarau-5b8ab6190/*

3. I graduated from *BelSUT* in 2014, *Faculty of Industrial and Civil Engineering*. 
Due to the current economic situation at that time and continuing to this day, I will not be able to find a good job in my specialty. 
So I decided to study programming, and I realized - I like it. Of course, I'm not a senior developer, 
but I learn new things every day and someday I will become a ~~hokage~~ senior front-end developer. Have a nice day;)

4. Skills: *html*, *css*, *JS*, *react*, *git*, *mongoDB*, *typeScript*.

5. ```
   const buttonCheck = {
    start: function () {
      const button = document.querySelector("#buttonCheck");
      const comment = document.querySelector("#sendComment");
      let text = comment.value;
      const answer = document.querySelector("#message");
      button.onclick = function checkPhoneAndComment() {
        //check comment
        if (comment.value !== "") {
          text += comment.value;
        } else comment.value = "vladnew91@gmail.com";
        //check telephon
        const re = /^(\s*)?(\+)?([- _():=+]?\d[- _():=+]?){12}(\s*)?$/;
        let myPhone = document.getElementById('phone').value;
        const valid = re.test(myPhone);
        if (valid) {
          myPhone = 'Номер верный!';
        } else myPhone = 'не верный!';
        answer.textContent = myPhone;
        return valid;
        };
      },
    };
    buttonCheck.start();
    ```

6. Finished courses:rsschool 2020q3 frontend stage1, JS it-camasutra, JS WebDev, seminars on YouTube regarding frontend and JS from Epam.

7. I was on courses at *Minsk State Linguistic University*, finished express courses with a native speaker. 
Today my E lavel is *pre-intermediate*.


