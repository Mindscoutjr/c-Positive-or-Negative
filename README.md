int n;
    cout<<"\nEnter your number";
    cin>>n;
    if(n>0)
    {
        
        cout<<"\nYour number is Positive";
    }
    else if (n<0)
    {
        cout<<"\nYour number is Negative"<<n;
    }
    else
    {
        cout<<"\nYou entered 0";
    }
    cout<<"This line is always printed";
    return 0;
