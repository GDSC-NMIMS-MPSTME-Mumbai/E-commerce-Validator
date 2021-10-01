# HACKTOBER Fest Clothing E-commerce Validator

![GDSC MPSTME Logo.png](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc5b6c0e2-a49c-4eb7-9262-12581114c92c%2FGDSC_MPSTME_Logo.png?table=block&id=01d9771a-45ab-4d89-8496-2936f07c784c&spaceId=79cc7a58-8052-4abf-99dd-041564524228&width=2000&userId=ca0b4db0-b2f3-4c54-8436-a0717191a95d&cache=v2)

### Task

---

Contributors must create a website that can validate the inputted data along with the image provided in the field of clothing.

### Problem Statement

---

- In this problem, you have to create a website for an ecommerce company which focuses on clothing wherein the user has to provide 2 inputs. One for product's description and another for the product's image(s).
- Now, for any image uploaded, you have to take out the features from the image and then validate them against the product's description that the user has provided. If it matches or is above a certain threshold, then the user has submitted the right details and gets an alert saying everything's good. Else, it tells the user what all details didn't match

### Example

---

- For instance, lets take the case of a T-Shirt that the Clothing Ecommerce company has to validate the data for:
    - User provides the T-Shirts description like "Red, rounded, half-sleeved tshirt" and provides an image like:
        
        ![Untitled](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F58c5a367-4932-43fe-9ff3-fa77aa0aa2f9%2FUntitled.png?table=block&id=abafc65b-5188-42d8-9adb-6f1794050940&spaceId=79cc7a58-8052-4abf-99dd-041564524228&width=2000&userId=ca0b4db0-b2f3-4c54-8436-a0717191a95d&cache=v2)
        
    - Now, in this image provided the color of the tshirt can be extracted to be "black" which isn't what the user entered. Then, in this case the user is shown that the color entered is "red" but the image has color "black".

### Technologies to be used

---

- You are supposed to make a React website with any backend. The only thing is that, it should be deployed and the end product should be a website.
