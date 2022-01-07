# Catalan数

~~~ cpp
inline int read()
{
  int s=0,w=1;char ch;
  while((ch=getchar())>'9'||ch<'0') if(ch=='-') w=-1;
  while(ch>='0'&&ch<='9') s=s*10+ch-'0',ch=getchar();
  return s*w;
}
~~~
