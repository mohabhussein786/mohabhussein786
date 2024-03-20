#include<iostream>

using namespace std;

class germany_langauge_exams
{
    private:
    int choice1;
    public:
    
    void set(int ch)
    {
        choice1 = ch;
    }
    
    void germany_exam()
    {
        cout<<"================= welcome to germany langauge exam =============="<<endl;
        cout<<"1.choices"<<endl;
        cout<<"2.true or false"<<endl;
        cout<<"3.fill spaces with a word from the list"<<endl;
        cout<<"4.match the following sentences"<<endl;
        cout<<"5.exit"<<endl;
        cout<<"enter exam what you want:"<<endl;
        cin>>choice1;
        
        switch(choice1)
        {
            case 1:
            if(choice1 == 1)
            {
                int number1;
                int number2;
                int number3;
                int number4;
                int number5;
                int number6;
               static int score1 = 1;
                cout<<"=============== welcome to germany coices exam ==============="<<endl;
                cout<<"what mean of (wasser):"<<endl;
                cout<<"      1.water         2.dog           3.cat"<<endl;
                cout<<"enter the correct answer:"<<endl;
                cin>>number1;
                
                if(number1 == 1 )
                {
                    cout<<"correct answer"<<endl;
                    
                    cout<<"your score is:"<<score1<<endl;
                }else{
                    cout<<"wrong answer"<<endl;
                    score1--;
                    cout<<"your score is:"<<score1<<endl;
                }
                cout<<"what mean of (hund):"<<endl;
                cout<<"      1.van        2.tea         3.dog"<<endl;
                cout<<"enter the correct answer:"<<endl;
                cin>>number2;
                if(number2 == 3)
                {
                    cout<<"correct answer"<<endl;
                    score1++;
                    cout<<"your score is:"<<score1<<endl;
                }
                else{
                    cout<<"wrong answer"<<endl;
                    
                    cout<<"your score is:"<<score1<<endl;
                }
                cout<<"what mean of (auf weidersehen):"<<endl;
                cout<<"        1.good morning          2.goodbye          3.good evening"<<endl;
                cout<<"enter the correct answer:"<<endl;
                cin>>number3;
                
                if(number3 == 2)
                {
                    cout<<"correct answer"<<endl;
                    score1++;
                    cout<<"your score is:"<<score1<<endl;
                }
                else{
                    cout<<"wrong answer"<<endl;
                    
                    cout<<"your score is:"<<score1<<endl;
                }
                cout<<"wie gehts (----)"<<endl;
                cout<<"        1.dir         2.du         3.ich"<<endl;
                cout<<"enter the correct answer:"<<endl;
                cin>>number4;
                
                if(number4 == 1)
                {
                    cout<<"correct answer"<<endl;
                    score1++;
                    cout<<"your score is:"<<score1<<endl;
                }
                else{
                    cout<<"wrong answer"<<endl;
                    cout<<"your score is:"<<score1<<endl;
                }
                cout<<"was ist deine (----):"<<endl;
                cout<<"       1.spreiche           2.muttersprache         3.khulshrank"<<endl;
                cout<<"enter the correct answer:"<<endl;
                cin>>number5;
                
                if(number5 == 2){
                    cout<<"correct answer"<<endl;
                    score1++;
                    cout<<"your score is:"<<score1<<endl;
                }
                else{
                    cout<<"wrong answer"<<endl;
                    cout<<"your score is:"<<score1<<endl;
                }
                
                cout<<"ich habe drei kinder,und dir:"<<endl;
                cout<<"         1.ich habe eine auto        2.ich habe ein haus       3.ich habe keine kinder"<<endl;
                cout<<"enter the correct answer:"<<endl;
                cin>>number6;
                
                if(number6 == 3)
                {
                    cout<<"correct answer"<<endl;
                    score1++;
                    cout<<"your score is:"<<score1<<endl;
                    
                }
                else{
                    cout<<"wrong answer"<<endl;
                    cout<<"your score is:"<<score1<<endl;
                }
                cout<<"your total score is:"<<score1<<endl;
            
                
            
            }
            break;
            
            case 2:
            int word1;
            int word2;
            int word3;
            int word4;
          static  int score2 = 0;
          cout<<"================ welcome to true or false exam =================="<<endl;
          cout<<"does (haben sie eine kinder) mean do you have a kids:"<<endl;
          cout<<"        1.true             2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>word1;
          if(word1 == 1){
          cout<<"correct answer"<<endl;
          score2++;
          cout<<"your score is:"<<score2<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              
              cout<<"your score is:"<<score2<<endl;
          }
          cout<<"does (wie gehts ihnen) mean how are you,man:"<<endl;
          cout<<"        1.true             2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>word2;
          if(word2 == 2 )
          {
              cout<<"correct answer:"<<endl;
              score2++;
              cout<<"your score is:"<<score2<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score2<<endl;
          }
          cout<<" vier plus acht gleich zwolf:"<<endl;
          cout<<"        1.true           2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>word3;
          if(word3 == 1)
          {
              cout<<"correct answer"<<endl;
              score2++;
              cout<<"your score is:"<<score2<<endl;
              
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score2<<endl;
          }
          
          cout<<"(geld)mean cion:"<<endl;
          cout<<"        1.true          2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>word4;
          
          if(word4 == 1)
          {
              cout<<"correct answer"<<endl;
              score2++;
              cout<<"your score is:"<<score2<<endl;
              cout<<"your total score is:"<<score2<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score2<<endl;
              cout<<"your total score is:"<<score2<<endl;
              
              
              
              
          }
          break;
          case 3:
          if(choice1 == 3)
          {
              int number1;
              int number2;
              int number3;
              int number4;
              int number5;
              static int score3 = 0;
              cout<<"=================== welcome to fill spaces with words from list  =================="<<endl;
              cout<<"(1.funf, 2.vier, 3.elf , 4.zehn)"<<endl;
              cout<<"question is: vier plus (----) gliech neun"<<endl;
              cout<<"enter the correct answer:"<<endl;
              cin>>number1;
              
              if(number1 == 1)
              {
                  cout<<"correct answer"<<endl;
                  score3++;
                  cout<<"your score is:"<<score3<<endl;
              }
              else{
                  cout<<"wrong answer"<<endl;
                  cout<<"your score is:"<<score3<<endl;
              }
              cout<<"(1.dein , 2.sie , 3.mein , 4.wir)"<<endl;
              cout<<"question is:(---) name ist mohab"<<endl;
              cout<<"enter the correct answer:"<<endl;
              cin>>number2;
              
              if(number2 == 3)
              {
                  cout<<"correct answer"<<endl;
                  score3++;
                  cout<<"your score is:"<<score3<<endl;
              }
              else{
                  cout<<"wrong answer"<<endl;
                  cout<<"your score is:"<<score3<<endl;
              }
              cout<<"(1.das , 2.soll , 3.was , 4.wie)"<<endl;
              cout<<"question is:was (---) das etwas"<<endl;
              cout<<"enter the correct answer:"<<endl;
              cin>>number3;
              
              if(number3 == 2)
              {
                  cout<<"correct answer"<<endl;
                  score3++;
                  cout<<"your score is:"<<score3<<endl;
              }
              else{
                  cout<<"wrong answer"<<endl;
                  cout<<"your score is:"<<score3<<endl;
              }
              cout<<"(1.frau , 2.mann , 3.madchen , 4.sohn)"<<endl;
              cout<<" question is:meine (---) heibt rahma "<<endl;
              cout<<"enter the correct answer:"<<endl;
              cout<<number4;
              
              if(number4 == 1)
              {
                  cout<<"correct answer"<<endl;
                  score3++;
                  cout<<"your score is:"<<score3<<endl;
              }
              else{
                  cout<<"wrong answer"<<endl;
                  cout<<"your score is:"<<score3<<endl;
              }
              cout<<"(1.mochte , 2.brauch , 3.will , 4.willst)"<<endl;
              cout<<" question is:(---)du einen kaffee"<<endl;
              cout<<"enter the correct answer"<<endl;
              cin>>number5;
              
              if(number5 == 4)
              {
                  cout<<"correct answer"<<endl;
                  score3++;
                  cout<<"your score is:"<<score3<<endl;
                  
              }
              else
              {
                  cout<<"wrong answer"<<endl;
                  cout<<"your score is:"<<score3<<endl;
              }
              cout<<"(1.milch ,2.salz ,3.sugar,4.tee)"<<endl;
              cout<<"question is:ich will einen tee mit milch und (---)"<<endl;
              cout<<"enter the correct answer:"<<endl;
              cin>>number5;
              
              if(number5 == 3)
              {
                  cout<<"correct answer"<<endl;
                  score3++;
                  cout<<"your score is:"<<score3<<endl;
              }
              else{
                  cout<<"wrong answer"<<endl;
                  cout<<"your score is:"<<score3<<endl;
              }
              
              
              cout<<"total score is:"<<score3<<endl;
          }
          
       
          
        }
        
        
    
        
        
    }


    
};
class spanish_langauge_exams{
    private:
    int choice3;
    public:
    void set2(int ch3)
    {
        choice3 = ch3;
    }
    void spanish_exams()
    {
        cout<<"=============== welcome to spanish langauge exams ================"<<endl;
        cout<<"1.choices"<<endl;
        cout<<"2.true or false"<<endl;
        cout<<"3.fill the spaces with a words from the list"<<endl;
        cout<<"4 complete the following sentences"<<endl;
        cout<<"5.translate into spanish"<<endl;
        cout<<"6.exit"<<endl;
         cout<<"enter what exam you want:"<<endl;
        cin>>choice3;
        
        switch(choice3)
        {
            case 1:
            int number1;
            int number2;
            int number3;
            int number4;
            int number5;
            static int score4 = 0;
            cout<<"=============== welcome to choices exam ================"<<endl;
            cout<<"what mean of (grasias)"<<endl;
            cout<<"       1.goodbye          2.thank you         3.hello"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number1;
            
            if(number1 == 2)
            {
                cout<<"correct answer"<<endl;
                score4++;
                cout<<"your score is:"<<score4<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score4<<endl;
            }
            cout<<"what mean of(si)"<<endl;
            cout<<"1.yes       2.no        3.also"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number2;
            if(number2 == 1)
            {
                cout<<"correct answer"<<endl;
                score4++;
                cout<<"your score is:"<<score4<<endl;
                
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score4<<endl;
            }
            cout<<"what mean of(Cómo estás)"<<endl;
            cout<<" 1.hello         2.bautiful     3.how are you"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number3;
            
            if(number3 == 3)
            {
                cout<<"correct answer"<<endl;
                score4++;
                cout<<"your score is:"<<score4<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score4<<endl;
            }
            cout<<"what mean of(qué deseas)"<<endl;
            cout<<" 1.what do you want     2.what else        3.whats up"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number4;
            
            if(number4 == 1)
            {
                cout<<"correct answer"<<endl;
                score4++;
                cout<<"your score is:"<<score4<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score4<<endl;
            }
            cout<<"what mean of(tienes un carro)"<<endl;
            cout<<" 1. do you have a kids    2.do you have a car      3.do you have villa"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number5;
            if(number5 == 2)
            {
                cout<<"correct answer"<<endl;
                score4++;
                cout<<"your score is:"<<score4<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score4<<endl;
            }
            cout<<"your total score is:"<<score4<<endl;
            
            case 2:
            int number6;
            int number7;
            int number8;
            int number9;
            int number10;
          static  int score5 = 0;
            cout<<"does (gata) mean cat"<<endl;
            cout<<"1.true      2.false"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number6;
            
            if(number6 == 1)
            {
                cout<<"correct answer"<<endl;
                score5++;
                cout<<"your score is:"<<score5<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                
                cout<<"your score is:"<<score5<<endl;
            }
            cout<<"does (caballo) mean dog"<<endl;
            cout<<"1.true    2.false"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number7;
            if(number7 == 2)
            {
                cout<<"correct answer"<<endl;
                score5++;
                cout<<"your score is:"<<score5<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score5<<endl;
            }
            cout<<"does (cuantas) mean how many"<<endl;
            cout<<" 1.true     2.false"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number8;
            if(number8 == 1)
            {
                cout<<"correct answer"<<endl;
                score5++;
                cout<<"your score is:"<<score5<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score5<<endl;
            }
            cout<<"does (qué significa eso?) mean what does that mean"<<endl;
            cout<<"1.true      2.false"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number9;
            if(number9 == 1)
            {
                cout<<"correct answer"<<endl;
                score5++;
                cout<<"your score is:"<<score5<<endl;
                
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score5<<endl;
            }
            cout<<"Una más una igual tres"<<endl;
            cout<<"1.true    2.false"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number10;
            if(number10 == 2)
            {
                cout<<"correct answer"<<endl;
                score5++;
                cout<<"your score is:"<<score5<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score5<<endl;
            }
            break;
            case 3:
            int number11;
            int number12;
            int number13;
            int number14;
            int number15;
           static int score6 = 0;
            cout<<"(1.llammo   2.llamas  3.soy    4.donde)"<<endl;
            cout<<"question is:me (---) mohab"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number11;
            if(number11 == 1)
            {
                cout<<"correct answer"<<endl;
                score6++;
                cout<<"your score is:"<<score6<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score6<<endl;
            }
            cout<<"(1.tal   2.que  3.soy   4.sois)"<<endl;
            cout<<"question is:(---) tal"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number12;
            if(number12 == 2)
            {
                cout<<"correct answer"<<endl;
                score6++;
                cout<<"your score is:"<<score6<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score6<<endl;
            }
            cout<<"(1.hablo   2.habla    3.soy   4.hablas)"<<endl;
            cout<<"question is:de donde (---)"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number13;
            if(number13 == 4)
            {
                cout<<"correct answer"<<endl;
                score6++;
                cout<<"your score is:"<<score6<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score6<<endl;
            }
            cout<<"(1.donde    2.sois     3.son   4.tal)"<<endl;
            cout<<"question is: de (---) sois"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number14;
            if(number14 == 1)
            {
                cout<<"correct answer"<<endl;
                score6++;
                cout<<"your score is:"<<score6<<endl;
                
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score6<<endl;
            }
            cout<<"(1.sampatica  2.habla     3.quapo    4.monero)"<<endl;
            cout<<"question is : mi amigo es (---)"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number15;
            if(number15 == 1)
            {
                cout<<"correct answer"<<endl;
                score6++;
                cout<<"your score is:"<<score6<<endl;
                
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score6<<endl;
            }
            break;
            case 5:
            int number16;
            int number17;
            int number18;
            int number19;
            static int score7 = 0;
            cout<<"================ welcome to translate into spanish ==================="<<endl;
            
            cout<<"first question is: hello my name is mohab"<<endl;
            cout<<" 1.hola me llamo mohab"<<endl;
            cout<<"2. hola ,como estas"<<endl;
            cout<<"3.hola,como de llamas"<<endl;
            cout<<"enter the correct answer:"<<endl;
            cin>>number16;
            if(number16 == 1)
            {
                cout<<"correct answer"<<endl;
                score7++;
                cout<<"your score is:"<<score7<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score7<<endl;
            }
            cout<<"second question is: mi amiga es rahma y ella es de mujar"<<endl;
            cout<<"1.my friend is mohab and he is a man"<<endl;
            cout<<"2.me hablo mohab"<<endl;
            cout<<"3.my girlfriend is rahma  and she is a woman"<<endl;
            
            cout<<"enter the correct answer:"<<endl;
            cin>>number17;
            
            if(number17 == 3)
            {
                cout<<"correct answer"<<endl;
                score7++;
                cout<<"your score is:"<<score7<<endl;
            }
            else{
                cout<<"wrong  answer"<<endl;
                cout<<"your score is:"<<score7<<endl;
            }
            cout<<"third question is: vosotros estamos:"<<endl;
            cout<<"1.we are good "<<endl;
            cout<<"2.they are good"<<endl;
            cout<<"3.i am good"<<endl;
            
            cout<<"enter the correct answer:"<<endl;
            cin>>number18;
            
            if(number18 == 1){
                cout<<"correct answer"<<endl;
                score7++;
                cout<<"your score is:"<<score7<<endl;
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score7<<endl;
            }
            cout<<"fourth question is: alto "<<endl;
            cout<<"1.short"<<endl;
            cout<<"2.tall"<<endl;
            cout<<"3.very tall"<<endl;
            
            cout<<"enter the correct answer:"<<endl;
            cin>>number19;
            
            if(number19 == 2)
            {
                cout<<"correct answer"<<endl;
                score7++;
                cout<<"your score is:"<<score7<<endl;
                
            }
            else{
                cout<<"wrong answer"<<endl;
                cout<<"your score is:"<<score7<<endl;
            }
            
            
        }
    }
};

class english_exam_languages{
  private:
  int choice4;
   void set4(int c4)
  {
      choice4=c4;
  }
  public:
  void english_exams()
  {
      cout<<"==================== welcome to english exam langauge ==================="<<endl;
      cout<<"1.paragrafh"<<endl;
      cout<<"2.true or false"<<endl;
      cout<<"3.fill the spaces"<<endl;
      cout<<"4.translate into arabic"<<endl;
      cout<<"enter what do you want:"<<endl;
      cin>>choice4;
      
      switch(choice4)
      {
          case 1:
          int number20;
          int number21;
          int number22;
          int number23;
          int number24;
          static int score8 = 0;
          
          cout<<"hello my name is mohab im 18 years old and i live in cairo und i born in kuwait und i have a sister only and i dont have any brothers"<<endl;
          cout<<"answer the following questions:"<<endl;
          cout<<"1.does mohab have brother:"<<endl;
          cout<<"     1.yes      2.no"<<endl;
          cout<<"choose the correct answer:"<<endl;
          cin>>number20;
          if(number20 == 2)
          {
              cout<<"correct answer"<<endl;
              score8++;
              cout<<"your score is:"<<score8<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score8<<endl;
          }
          cout<<"2.does mohab 18 year old:"<<endl;
          cout<<"1.yes        2.no"<<endl;
          cout<<"choose the correct answer:"<<endl;
          cin>>number21;
          if(number21==1)
          {
              cout<<"correct answer"<<endl;
              score8++;
              cout<<"your score is:"<<score8<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score8<<endl;
          }
          
          break;
          case 2:
          int number25;
          int number26;
          int number27;
          int number28;
          static int score11 = 0;
          
          cout<<"===================== welcome to true or false ======================"<<endl;
          cout<<"questions of qeoghrafy"<<endl;
          
          cout<<"first question is: does russia is the biggest country in the world ():"<<endl;
          cout<<"         1.true         2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number25;
          
          if(number25 == 1)
          {
              cout<<"correct answer"<<endl;
              score11++;
              cout<<"your score is:"<<score11<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score11<<endl;
          }
          cout<<"second question is: does mongolia in europa ():  "<<endl;
          cout<<"    1.true        2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number26;
          if(number26 == 2)
          {
              cout<<"correct answer"<<endl;
              score11++;
              cout<<"your score is:"<<score11<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score11<<endl;
          }
          cout<<"third question is: does the longest nile in the world is in brazil country ():"<<endl;
          cout<<"       1.true        2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number27;
          if(number27 == 2)
          {
              cout<<"correct answer"<<endl;
              score11++;
              cout<<"your score is:"<<score11<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score11<<endl;
              
          }
          cout<<"fourth question is:are in south america is there 23 country ():"<<endl;
          cout<<" 1.true       2.false"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number28;
          if(number28 == 1)
          {
              cout<<"correct answer"<<endl;
              score11;
              cout<<"your score is:"<<score11<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score11<<endl;
              
          }
          break;
          case 3:
          int number29;
          int number30;
          int number31;
          int number32;
          static int score12 = 0;
          cout<<"================== welcome to fill the spaces exam ==================="<<endl;
          cout<<"first question is:who is josef stallen:"<<endl;
          cout<<"(1.he is soviet,2.he is american,3.he is mexican)"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number29;
          if(number29 == 1)
          {
              cout<<"correct answer"<<endl;
              score12++;
              cout<<"your score is"<<score12<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score12<<endl;
          }
          cout<<"second question is:where is germany:"<<endl;
          cout<<"(1.north america,2.south america,3.europe)"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number30;
          if(number30 == 3)
          {
              cout<<"correct answer"<<endl;
              score12++;
              cout<<"your score is:"<<score12<<endl;
              
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score12<<endl;
          }
          cout<<"third question is:world war 1 begin in:"<<endl;
          cout<<"(1.1933,2.1990,3.1914)"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number31;
          if(number31==3)
          {
              cout<<"correct answer"<<endl;
              score12++;
              cout<<"your score is:"<<score12<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score12<<endl;
          }
          cout<<"fourth question is:world war 2 begin in:"<<endl;
          cout<<"(1.1939.1955.1930)"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number32;
          if(number32==1)
          {
          cout<<"correct answer"<<endl;
          score12++;
          cout<<"your score is:"<<score12<<endl;
          
          }
          
          
          break;
          
          case 4:
          int number33;
          int number34;
          int number35;
          
          static int score13 = 0;
          cout<<"=================== welcome to translate exam from english to spanich  ==================="<<endl;
          cout<<"first question is:whats your name:"<<endl;
          cout<<"1.yo qiuero pagar"<<endl;
          cout<<"2.como te llamas"<<endl;
          cout<<"3.como se llama"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number33;
          if(number33 == 2)
          {
              cout<<"correct answer"<<endl;
              score13++;
              cout<<"your score is:"<<score13<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score13<<endl;
          }
          cout<<"second question is:i have three brothers"<<endl;
          cout<<"1.yo tengo tres hermanos"<<endl;
          cout<<"2.yo no tengo dos hermanas"<<endl;
          cout<<"3.yo qiuero una hermana"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number34;
          if(number34 == 1)
          {
              cout<<"correct answer"<<endl;
              score13++;
              cout<<"your score is:"<<score13<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score13<<endl;
              
          }
          cout<<"third question is:do you need help"<<endl;
          cout<<"1.necesitas ayuda"<<endl;
          cout<<"2.necesitas pregonta"<<endl;
          cout<<"3.necesitas boligrafo"<<endl;
          cout<<"enter the correct answer:"<<endl;
          cin>>number35;
          if(number35 == 1)
          {
              cout<<"correct answer:"<<endl;
              score13++;
              cout<<"your score is:"<<score13<<endl;
          }
          else{
              cout<<"wrong answer"<<endl;
              cout<<"your score is:"<<score13<<endl;
          }
      }
  }
};

int main()
{
    
    //made by mohab
    cout<<"================ made by mohab mohamed hussein =================="<<endl;
    string name;
    cout<<"ente your name:"<<endl;
    cin>>name;
    
    cout<<"welcome "<<name <<"to our langauges exams"<<endl;

    while(1){
        
    int choice;
    cout<<"================ welcome to langauges exams ==============="<<endl;
    cout<<"1.germany langauge exams"<<endl;
    cout<<"2.spanich langauge exams"<<endl;
    cout<<"3.english langauge exams"<<endl;
    cout<<"4.exit"<<endl;
    
    cout<<"enter langauge exam you want:"<<endl;
    cin>>choice;
    
    switch(choice)
    {
        case 1:
        germany_langauge_exams g1;
        g1.germany_exam();
        break;
        case 2:
        spanish_langauge_exams s1;
        s1.spanish_exams();
        break;
        case 3:
        english_exam_languages e1;
        e1.english_exams();
        break;
        case 4:
        exit(1);
        
    }
    

}
}

























