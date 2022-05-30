# Ratko Kostov 183089

![FINALDIAGRAM](https://user-images.githubusercontent.com/86716668/169287700-2ee9c35a-b5d5-43cf-960f-10626ba666eb.jpg)


3. Цикломатската комплекснот на задачата е 9. Пресметав така што ги избројав сите моменти на одлука односно (if statemants) во оваа задача
ги има 8 и на овие додаваме +1 за да ја имаме комплетно пресметната Цикломатската комплексност.

4. 
Прв тест случај: Внес на празна листа
Втор тест случај: Внес на не квадратна матрица (Not perfect square)
Трет тест случај: ["0","#","0", "#","0","#", "0","#","#"]

Првиот тест случај ми ја покрива првата if одлука кога таа е точна и фрла IllegalArgumentException.

Вториот тест случај ми ја покрива првата if одлука кога таа е неточна и втората if одлука кога таа е точна
и фрла IllegalArgumentException.

Со овие 2 теста ги покривам IllegalArgumentException.

Третиот тест пример е листа таква каква што се бара односно квадратна матрица исполнета со 0 и #.
Во овој тест пример намерно ги подредив елементите така што во целиот for циклус ќе ги изминам
сите случаеви односно сите одлуки кога не се точни и кога се точни. 

Па така се доволни 3 теста за да се задоволи EveryStatemant критериумот. На сликата подолу е дадена
патеката по која изминуват сите 3 тест примера.

![EveryStatemant](https://user-images.githubusercontent.com/86716668/169293475-3d076a7f-f0e1-4549-88a3-6b3702a9e770.jpg)


5. За EveryBranch критериумот ги користев истите тест примери и ми беа доволни за да се задоволи истиот.
Во прилог е сликата на гранките кои ги изминуваат тест примерите.

Прв тест случај: Внес на празна листа
Втор тест случај: Внес на не квадратна матрица (Not perfect square)
Трет тест случај: ["0","#","0", "#","0","#", "0","#","#"]

Со првите 2 тест примера ги покрив IllegalArgumentException.

Со 3тиот тест случај ги корив гранки од задчата со што го задоволува критериумот на EveryBranch.

![EveryBranch](https://user-images.githubusercontent.com/86716668/169294822-5ab13479-736b-4f1c-9490-1519ede2def8.jpg)


7. Бидејќи ги користев истите тест случаеви и за двата критериума и ми беа доволни 3 тест случаеви
   за да го покријам целиот тек на задачата ги искористив истите тест примери и за Unit тестовите.
   Креирав една празна листа, листа со два елементи ( Not perfect Square)  и листа според условите на задчата
   редоследот на елементи го направив така што ќе ги покрие сите одлуки и кога се точни и кога не се точни.
   Односно следнава листа ["0","#","0", "#","0","#", "0","#","#"]
   
   Дефинирав два објекти од класата IllegalArgumentException каде што ги користам за првите два тест примера
   каде што треба да фрлат exception и со помош на assetTrue() проверував според пораката дали станува збор
   за празна листа или листа која не е матрица.
   
   За третиот unit тест креирав листа со output кој го очекувам.
   Со помош на assertEquals ги споредив листите со резултатот од функцијата со листата што ја земав како input  и  листата со очекуваниот output.
   
   Овие 3 assert  ми поминаа успешно па така и целиот тест ми помимна успешно.
   
   Бидејќи и за двата критериуми ми се доволни само еден тест кој ќе ги тестира 3-те тестови
     Прв тест случај: Внес на празна листа
     Втор тест случај: Внес на не квадратна матрица (Not perfect square)
     Трет тест случај: ["0","#","0", "#","0","#", "0","#","#"]
     
     Креирав само еден тест кој ќе важи за двата критериуми.
