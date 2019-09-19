# Darya Drazdouskaya

## 📡 Contact info
* Phone: [+375293644414](tel:+375293644414)
* Gmail: [darya.drazdouskaya@gmail.com](mailto:darya.drazdouskaya@gmail.com)
* Telegram: [@d_konti](https://t.me/d_konti)
 

## 💭 Summary
While I was a student at the HTML Academy, I fell in love with semantics and the possibilities of creating accessible and user-friendly interfaces. HTML and CSS were becoming my best friends during those months, but then I understood that for developing myself as a web-developer I need to go deep into Javascript. That's why I became a student of the Rolling Scopes school :)

I'm also interested in UX/UI design and definitely will learn more about it in the near future.
 

## 💪 Skills
* HTML
* CSS
* Javascript
* Less
* BEM
* GIT
* VS Code
 

## 📈 Experience
Here are my study projects for HTML Academy intensives:
* Nёrds - design studio website.
* Cat Energy - online store of cat's fitness food.
* Kekstagram - image viewing service.


## 🎓 Education
* march-august 2019 - [HTML Academy's courses and intensives](https://htmlacademy.ru/profile/id896583);
* 2019 - [Codecademy's courses](https://www.codecademy.com/profiles/D_Darya);
* february 2019 - [MinskCSS Workshop #2 "CSS Grid Layout"](https://vk.com/event175397192);
* 2018-2019 - [MinskCSS#5](https://vk.com/event173256364)/[MinskCSS#6](https://vk.com/event179507949) and [MinskJS#5](https://vk.com/event177067615) meetups;
* december 2018 - [The Rolling Scopes #52](https://vk.com/therollingscopes) meetup;
* december 2018 - [WSD conference](https://wsd.events/2018/12/01/).
 

## 💻 Code example
```Javascript
var ScaleValue = {
  DEFAULT: 100,
  MIN: 25,
  MAX: 100,
  STEP: 25
};

var imgPreviewSizeFieldset = document.querySelector('.img-upload__scale');
var scaleValue = document.querySelector('.scale__control--value');
var imgPreview = window.form.imgPreview;

// Function that change the scale of the image
var zoomImg = function (sizeValue) {
  imgPreview.style.transform = 'scale(' + sizeValue / 100 + ')';
};

// Function that change the value of the .scale__control - value field
var onChangeSizeImgPreview = function (evt) {
  var sizeValue = parseInt(scaleValue.value, 10);
  if ((evt.target.classList.contains('scale__control--bigger') 
  && sizeValue < ScaleValue.MAX)) {
    scaleValue.value = sizeValue + ScaleValue.STEP + '%';
    sizeValue += ScaleValue.STEP;
    zoomImg(sizeValue);
  } else if ((evt.target.classList.contains('scale__control--smaller') 
    && sizeValue > ScaleValue.MIN)) {
    scaleValue.value = sizeValue - ScaleValue.STEP + '%';
    sizeValue -= ScaleValue.STEP;
    zoomImg(sizeValue);
  }
};

imgPreviewSizeFieldset.addEventListener('click', onChangeSizeImgPreview);
```
To see more you can visit my [Github page](https://github.com/darya-d).
 
 
## 🇬🇧 English
In 2016 I had passed the Streamline School's exam and got certificates for the B1-B2 level. Since then I’ve been using English only while travelling in Europe, practicing in Lingualeo app and watching Netflix 😉
