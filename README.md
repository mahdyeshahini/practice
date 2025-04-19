تمرین های آردوینو

عنوان آزمایش : LED به صورت چشمک زن یک ثانیه روشن و یک ثانیه خاموش شود

وسایل مورد نیاز : بردبورد ، میکرو کنترلر ، LED ، مقومت 220 اهم

شرح آزمایش : 

کد آزمایش : 

int led =13;
void setup () { 
pinMode (led, OUTPUT);  
} 
Void loop () { 
digitalWrite (led, HIGH); 
delay (1000); 
digitalWrite (led, LOW); 
delay (1000); 
}


