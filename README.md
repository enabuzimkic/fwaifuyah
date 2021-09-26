#include<iostream>
using namespace std;
int main () 
{
int godina_rodjenja,mjesec_rodjenja;
int trenutna_godina=2021;
int trenutni_mjesec=9;

cout<<"Unesite vasu godinu i mjesec rodjenja."<<endl;
cin>>godina_rodjenja>>mjesec_rodjenja;
if (mjesec_rodjenja==12){
cout<<"Imate "<<trenutna_godina-godina_rodjenja-1<<" godina i "<<trenutni_mjesec<<" mjeseci.";
}
if else (mjesec_rodjenja==11)[
cout<<"Imate "<<trenutna_godina-godina_rodjenja-1<<" godina i "<<trenutni_mjesec-1<<" mjeseci.";
}
if else (mjesec_rodjenja==10){
cout<<"Imate "<<trenutna_godina-godina_rodjenja-1<<" godina i "<<trenutni_mjesec-mjesec_rodjenja<<" mjeseci";
}
return 0;
}
