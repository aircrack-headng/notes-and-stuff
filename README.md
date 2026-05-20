# notes-and-stuff
notes for cybersec theory and ocassional attempts at Comp prog
notes 5/20/26 1930 with notes of ranting
C++ vectors
syntax eg:
PS:dont forget to use rand/mt19937 for randomisdation problems 
  int main(){
    int v[*insert limit number+1*]
reading:
  int a[101], n, i;
  fin>>n;
  for (i=1; i<=n; i++)
    fin>>a[i]
 for writing use fout instead obviously
alternate version:cin/cout
sum of elements:
  int v[100]
  int main(){
    int i, n, s=0;
    cin>>n;
    for(i=1; i<=n;i++){
      cin>>v[i];
      s= s+v[i]
read S and ur done
maxiumum/minimum using vmax/vmin
reverse order:
for(i=n-1; i>=0; 1--){
  cout<<a[i]<<"";
why ts basically SQL atp from now on but whatever
  I SHOULD BE BUG BOUNTY HUNTING BUT NOOOO ITS 11PM AND I HAVE A COMPETITION TOMORROW
inserting x on postion k:
for(i=n+1;i>k;i--)
a[i]=a[i-1]
a[k]=x
n++
elimination works the same but uses i<=n-1 in FOR and a[i]=a[i+1]
ehm statistical frequence or something...ISTG im not even in 8th grade doing this ABSOLUTE BULLSHIT.at least its not 11th grade material HOLY SHIT anywho rant over locked back in
YES I NOTICED THE MISTAKES SHUSH I KNOW THIS IS RECAP NOT PERFECTIONISM
int n,c
cin>>n
while(n>0)
c=n%10
v[c]++
n=n/10
for(c=0;c<10;c++)
if(v[c]!=0)
cout<<c<<' '<<v[c]<<endl
sum of something idk either goes like 
nrc=nrc+v[c] instead of line 44
END of study sesh:2324
material
