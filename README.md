#include <iostream>
using namespace std;
int main()
{
    int pizza, tip;

    cout << "code#        MENU                            PRICE "<<endl;
    cout << " "<<endl;
    cout << "1      ZESTY GARLIC CHICKEN                  P209.00"<<endl;
    cout << "2      FIERY HAWAIIAN                        P189.00"<<endl;
    cout << "3      EXTRAVAGANZZA                         P209.00"<<endl;
    cout << "4      KALAMATA TOMATO                       P209.00"<<endl;
    cout << "5      POTATO BACON                          P209.00"<<endl;
    cout << "6      VEGGIE                                P189.00"<<endl;
    cout << "7      PULLED PORK BBQ                       P209.00"<<endl;
    cout << "8      PEPPERONI FEAST                       P99.00"<<endl;
    cout << "9      MEATZZA                               P189.00"<<endl;
    cout << "10     HAWAIIAN CLASSIC                      P99.00"<<endl;
    cout << "11     HAM & CHEESE                          P99.00"<<endl;
    cout << "12     DOMINO'S DELUXE                       P189.00"<<endl;

    cout << " "<<endl;
    cout << "Enter the code # of your order: ";
    cin >> pizza;

    cout << "Enter the amount of your tip: ";
    cin >> tip;

        switch (pizza)
    {
        case 1:
            cout <<endl<<"SUMMARY OF PAYMENT"<<endl<< "ZESTY GARLIC CHICKEN  P209"<<endl<<"Total Payment         "<<"P"<< 209 + tip;
            break;
        case 2:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "FIERY HAWAIIAN   P189"<<endl<<"Total Payment    "<<"P"<< 189 + tip;
            break;
        case 3:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<< "EXTRAVAGANZZA    P209"<<endl<<"Total Payment    "<<"P"<< 209 + tip;
            break;
        case 4:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "KALAMATA TOMATO   P209"<<endl<<"Total Payment     "<<"P"<< 209 + tip;
            break;
        case 5:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "POTATO BACON     P209"<<endl<<"Total Payment    "<<"P"<<209 + tip;
            break;
        case 6:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "VEGGIE         P189"<<endl<< "Total Payment  "<<"P"<< 189 + tip;
            break;
         case 7:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "PULLED PORK BBQ   P209"<<endl<<"Total Payment     "<<"P"<< 209 + tip;
            break;
        case 8:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "PEPPERONI FEAST   P99"<<endl<<"Total Payment     "<<"P"<< 99 + tip;
            break;
        case 9:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "MEATZZA        P189"<<endl<<"Total Payment  "<<"P"<<189 + tip;
             break;
        case 10:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "HAWAIIAN CLASSIC    P99          "<<endl<<"Total Payment       "<<"P"<< 99 + tip;
            break;
        case 11:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "HAM & CHEESE     P99.00"<<endl<<"Total Payment    "<<"P"<<99 + tip;
            break;
        case 12:
             cout <<endl<<"SUMMARY OF PAYMENT"<<endl<<  "DOMINO'S DELUXE P189"<<endl<<"Total Payment   "<<"P"<< 189 + tip;
            break;
        default:

            cout << "Error! enter valid code number";
            break;
    }

    return 0;
}
