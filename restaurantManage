#include<bits/stdc++.h>
using namespace std;

class restorent{
    int n{0};
    int item{0};
public:

    struct price{
        int startIt1{0},startIt2{0},startIt3{0};
        int mainIt1{0},mainIt2{0},mainIt3{0};
        int desIt1{0},desIt2{0},desIt3{0};
    };
    price p;

    int prising()
    {
        int total{0};

//first

        if(p.startIt1 > 0 )
        {
            total=total+((p.startIt1)*250);
        }
        if (p.startIt2 > 0 )
        {
            total=total+((p.startIt2)*350);
        }
        if (p.startIt3 > 0 )
        {
            total=total+((p.startIt3)*450);
        }

//second

        if(p.mainIt1 > 0 )
        {
            total=total+((p.mainIt1)*250);
        }
        if(p.mainIt2 > 0 )
        {
            total=total+((p.mainIt2)*350);
        }
        if(p.mainIt3 > 0 )
        {
            total=total+((p.mainIt3)*450);
        }

//thied

        if(p.desIt1 > 0 )
        {
            total=total+((p.desIt1)*250);
        }
        if(p.desIt2 > 0 )
        {
            total=total+((p.desIt2)*350);
        }
        if(p.desIt3 > 0 )
        {
            total=total+((p.desIt3)*450);
        }

        cout<<"Your total payable ammount is "<<total<<", please pay your payment and visit again !!";
    }

    int billing()
    {
        cout<<flush;
        cout<<"Your order ditelas.. "<<endl;

        cout<<"From starters.. "<<endl;
        if(p.startIt1 > 0 || p.startIt2 > 0 || p.startIt3 > 0 )
        {
            if(p.startIt1 > 0 )
            {
                cout<<"You have entered "<<p.startIt1<<" item 1 "<<endl;
                cout<<"Whose total cost is "<<((p.startIt1)*250)<<endl;
            }
            if (p.startIt2 > 0 )
            {
                cout<<"You have entered "<<p.startIt2<<" item 2 "<<endl;
                cout<<"Whose total cost is "<<((p.startIt2)*350)<<endl;
            }
            if (p.startIt3 > 0 )
            {
                cout<<"You have entered "<<p.startIt3<<" item 3 "<<endl;
                cout<<"Whose total cost is "<<((p.startIt3)*450)<<endl;
            }

        } else{
            cout<<"You have entered nothing from Starters "<<endl;
        }

        cout<<"From Main Course.. "<<endl;
        if(p.mainIt1 > 0 || p.mainIt2 > 0 || p.mainIt3 > 0 )
        {
            if(p.mainIt1 > 0 )
            {
                cout<<"You have entered "<<p.mainIt1<<" item 1 "<<endl;
                cout<<"Whose total cost is "<<((p.mainIt1)*250)<<endl;
            }
            if(p.mainIt2 > 0 )
            {
                cout<<"You have entered "<<p.mainIt2<<" item 2 "<<endl;
                cout<<"Whose total cost is "<<((p.mainIt2)*350)<<endl;
            }
            if(p.mainIt3 > 0 )
            {
                cout<<"You have entered "<<p.mainIt3<<" item 3 "<<endl;
                cout<<"Whose total cost is "<<((p.mainIt3)*450)<<endl;
            }


        } else{
            cout<<"You have entered nothing from Main Course "<<endl;
        }

        cout<<"From Dessert.. "<<endl;
        if (p.desIt1 > 0 || p.desIt2 > 0 || p.desIt3 > 0 )
        {
            if(p.desIt1 > 0 )
            {
                cout<<"You have entered "<<p.desIt1<<" item 1 "<<endl;
                cout<<"Whose total cost is "<<((p.desIt1)*250)<<endl;
            }
            if(p.desIt2 > 0 )
            {
                cout<<"You have entered "<<p.desIt2<<" item 2 "<<endl;
                cout<<"Whose total cost is "<<((p.desIt2)*350)<<endl;
            }
            if(p.desIt3 > 0 )
            {
                cout<<"You have entered "<<p.desIt3<<" item 3 "<<endl;
                cout<<"Whose total cost is "<<((p.desIt3)*450)<<endl;
            }

        } else{
            cout<<"You have entered nothing from Dessert "<<endl;
        }
        int asd{0};
        cout<<"Enter 1 to conferm yor order or 0 to reorder ";
        cin>>asd;
        if (asd==1)
        {
            prising();
            
        }
        if (asd==0)
        {
            showData();
        } else{
            cout<<"Go Run Away !!"<<endl;
        }
    }

    int starter()
    {
        cout<<"1. Item "<<endl;
        cout<<"2. Item "<<endl;
        cout<<"3. Item "<<endl;
        cout<<"0. Done "<<endl;
        cin>>item;
        if (item==1)
        {
            p.startIt1++;
        }
        if (item==2)
        {
            p.startIt2++;
        }
        if (item==3)
        {
            p.startIt3++;
        }
        if (item==0)
        {
            showData();
        }
        showData();
    }
    int mainCourse()
    {
        cout<<"1. Item "<<endl;
        cout<<"2. Item "<<endl;
        cout<<"3. Item "<<endl;
        cout<<"0. Done "<<endl;
        cin>>item;
        if (item==1)
        {
            p.mainIt1++;
        }
        if (item==2)
        {
            p.mainIt2++;
        }
        if (item==3)
        {
            p.mainIt3++;
        }
        if (item==0)
        {
            showData();
        }
        showData();
    }

    int dessert()
    {
        cout<<"1. Item "<<endl;
        cout<<"2. Item "<<endl;
        cout<<"3. Item "<<endl;
        cout<<"0. Done "<<endl;
        cin>>item;
        if (item==1)
        {
            p.desIt1++;
        }
        if (item==2)
        {
            p.desIt2++;
        }
        if (item==3)
        {
            p.desIt3++;
        }
        if (item==0)
        {
            showData();
        }
        showData();
    }

    int showData(){
        cout<<"Welcome to the Restorent "<<endl;
        cout<<"Enter 1 for Starter "<<endl;
        cout<<"Enter 2 for Main Course "<<endl;
        cout<<"Enter 3 for Dessert "<<endl;
        cout<<"0 for Done";
        cin>>n;
        if (n==1)
        {
             starter();
        }
        if (n==2)
        {
             mainCourse();
        }
        if (n==3)
        {
             dessert();
        }
        if (n==0)
        {
             billing();
        }
        else{
            cout<<"Enter Valid Option !!";
            showData();
        }
    }

};

int main()
{
    restorent ob1;
    ob1.showData();

    return 0;
}
