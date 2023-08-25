
# Assignment 3 - Personal Detail Form



## 🔗 Links
[Git hub repo link](https://github.com/manasa8910/personal-detail-form)

[Hoisted link](https://manasa8910.github.io/personal-detail-form/)


## HTML

#### Please refer the index.html file in the github repo


The salutation field uses label, select, option tags

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/79169d66-b9d3-45cd-b763-c32abbe35e42)


```bash
    <p>Personal details</p>

    <form>
      <label
        >Salutation <br />
        <select>
          <option>--None--</option>
          <option>Mr.</option>
          <option>Mrs.</option>
        </select> </label
      ><br />
```

The name field uses label and input tag with type text

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/b7a00ae0-173e-4781-8b29-e15f6db3ac4e)

```bash
      <label for="name"
        ><br />
        First Name:
        <input type="text" name="name" placeholder="abcd" /><br /><br />
        Last Name:
        <input type="text" name="name" placeholder="abcd" /> </label
      ><br />
```

The gender field uses label and input tag with type radio

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/f8402774-5c1e-41d3-be9d-ce7753791ae8)

```bash
      <label for="gender"
        ><br />
        Gender:
        <input type="radio" name="gender" /> Male
        <input type="radio" name="gender" /> Female </label
      ><br />
```

The email field uses label and input tag with type email

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/705d1894-bfec-4274-92ec-e3e0cb399121)

```bash
      <label for="email"
        ><br />
        Email:<input type="email" name="email" value="abc@gmail.com" /> </label
      ><br />
```

The DOB field uses label and input tag with type date

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/41f9f6ab-cc02-408a-a37c-d568d0cd364f)

```bash
      <label for="Dob"
        ><br />
        Date of birth:<input type="date" name="Dob" /> </label
      ><br />
```

The Address field uses label and textarea tag

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/44348d1f-36f9-45b9-a8f1-da092ae35eb0)

```bash
      <label for="Address"
        ><br />
        Address:<br />
        <textarea name="Address" cols="30" rows="5"></textarea></label
      ><br />
      <br />
```

The Submit field uses label and input tag with type submit

![image](https://github.com/manasa8910/personal-detail-form/assets/67619299/730310f9-1025-4d21-9c82-41d1acd92250)

```bash
      <input type="submit" />
```
