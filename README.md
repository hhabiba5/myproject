#include <iostream>
#include "vehicles.h"
#include "soldiers.h"
using namespace std;

int main()
{

    do {
            int commands;
             cout << "welcome to army management/n";
             cout<< "give your army a command/n";
             cout<< "1.attack/n";
             cout<<"2.defend/n";
             cout<<"3.report/n";
             cin >> commands;


            switch(commands) {

                case 1 : //the army will attack
                    int whoattack;
                    
                    cout << "lets do it!/n";
                    cout << "which part of the army do you prefer to perform the attack?/n";
                    cout << "1.soldiers/n";
                    cout << "2.vehicles/n";
                    cout << "3.both at once!/n";
                    
                    
                    cin  >> whoattack;
                    
                    
                    switch (whoattack){

                     case 1://only soldiers attack





                     case 2://only vehicles attack
                         void ballista::attack()

                         void catapult::attack()

                         void seigeTower::attack()

                      //end



                     case 3://soldiers and vehicles attack
                         
                      void ballista::attack()

                      void catapult::attack()

                      void seigeTower::attack()
                      // the next is solders functions


                    }




                case 2 : // army defend
                
                    cout<<"army is defending!/n";
                    
                    //vehicles move
                    
                    void catapult::move()
                    void ballista::move()
                    void seigeTower::move()
                    
                         //soldiers defend 
                         
                    void archers :: defAction()
                    void infantry:: defAction()
                    void knights:: defAction()
                    




                case 3 : // everyone reports itself
                          void catapult::report()
                          void catapult::report()
                          void seigeTower::report()



            }
    }
    return 0;
}
