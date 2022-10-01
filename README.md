# Program-C-_TLS22
//Program ini hanyalah program sederhana
//Mencari Harga Jual Merchandise K-Pop

#include <iostream>
#define WON_RUPIAH 10.63

using namespace std;


int main()
{
    float purchase_price, selling_price, won, percent, selling_price_won;
    
    cout <<"Enter Purchase Price : ";
    cin >>won;
    
    cout <<"Enter Persentase : ";
    cin >>percent;
    
    purchase_price = won * WON_RUPIAH;
    selling_price = purchase_price - (purchase_price * percent);
    
    cout <<"Purchase Price Album in Rupiah : "<<purchase_price<<"\n";
    cout <<"Selling Price Album : "<<selling_price<<"\n";
    
    cout <<"Enter Purchase Price PC : ";
    cin >>won;
    cout <<"Enter Persentase Penurunan : ";
    cin >>percent;
    
    purchase_price = won * WON_RUPIAH;
    selling_price = purchase_price - (purchase_price * percent);
    
    cout <<"Purchase Price PC in Rupiah : "<<purchase_price<<"\n";
    cout <<"Selling Price Album in Rupiah : "<<selling_price<<"\n";
    
    return 0;
}
