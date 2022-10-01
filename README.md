# Program-C-_TLS22
Program ini hanyalah program sederhana
#include <iostream>
#define WON_RUPIAH 10.63
using namespace std;

int main()
{
    float purchase_price,insurance, percent_1, percent_2, tax_base_value,
    shipping, purchase_price_rupiah, import_duty, goods_vat, price_paid_album,
    price_paid_pc;
    
    cout <<"Enter Purchase Price Album : ";
    cin >>purchase_price;
    cout <<"Enter Shipping : ";
    cin >>shipping;
    cout <<"Enter Insurance : ";
    cin >>insurance;
    cout <<"Enter Persentase Customs : ";
    cin >>import_duty;
    cout <<"Enter Persentase PPN : ";
    cin >>percent_2;
    
    
    tax_base_value = purchase_price + shipping + insurance;
    purchase_price_rupiah = tax_base_value * WON_RUPIAH;
    import_duty = percent_1 * purchase_price_rupiah;
    goods_vat = percent_2 * (purchase_price_rupiah + import_duty);
    price_paid_album = purchase_price_rupiah + import_duty + goods_vat;
    
    cout <<"Tax Base Value : "<<tax_base_value<<"\n";
    cout <<"Purchase Price in Rupiah : "<<purchase_price_rupiah<<"\n";
    cout <<"Import Duty : "<<import_duty<<"\n";
    cout <<"Goods Vat : "<<goods_vat<<"\n";
    cout <<"Selling Price Album : "<<price_paid_album<<"\n";
    
    
    cout <<"Enter Purchase Price PC : ";
    cin >>purchase_price;
    cout <<"Enter Shipping : ";
    cin >>shipping;
    cout <<"Enter Insurance : ";
    cin >>insurance;
    cout <<"Enter Persentase Customs : ";
    cin >>import_duty;
    cout <<"Enter Persentase PPN : ";
    cin >>percent_2;
    
    
    tax_base_value = purchase_price + shipping + insurance;
    purchase_price_rupiah = tax_base_value * WON_RUPIAH;
    import_duty = percent_1 * purchase_price_rupiah;
    goods_vat = percent_2 * (purchase_price_rupiah + import_duty);
    price_paid_pc = purchase_price_rupiah + import_duty + goods_vat;
    
    cout <<"Selling Price PC : "<<price_paid_pc<<"\n";
    
    cout <<"\nCatalog Selling Price Per Item"<<endl;
    cout <<"Price Album : "<<price_paid_album<<endl;
    cout <<"Price PC : "<<price_paid_pc;


    return 0;
}
