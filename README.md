local iOi1iloIljIo0=(getfenv and getfenv(1)) or _ENV or _G
local joOOjljoj0OlI,l1O1ILOI10l=string.byte,string.char
local function iIjlLilj(iI00l0OilLL0,jii101i0)
local LIo1o10=""
local iloilOiOlIIjL=#jii101i0
for i0jo1Il=1,#iI00l0OilLL0 do LIo1o10=LIo1o10..l1O1ILOI10l((joOOjljoj0OlI(iI00l0OilLL0,i0jo1Il)-joOOjljoj0OlI(jii101i0,(i0jo1Il-1)%iloilOiOlIIjL+1))%256) end
return LIo1o10
end
local jLOiijIioOj=iOi1iloIljIo0[iIjlLilj("b\230\234I\201V","\239\129~\228f\226\029")]
local iL0jiI0lLjj0oL=iOi1iloIljIo0[iIjlLilj("\155 ;\145\0260","(\172\201")][iIjlLilj("\142\246\152","\027\1296")]
local iLj1iL=iOi1iloIljIo0[iIjlLilj("\185\164\004\166\224","EC\162:{")][iIjlLilj("\023\140\136E;\180","\180\029\026\226\218@\162")]
local L0iILo=iOi1iloIljIo0[iIjlLilj("_J\242\008","\242\233~\160")][iIjlLilj("\242\241\021\135~","\140\133\166\024\0122")]
local jIoljOlj11IIIL=iOi1iloIljIo0[iIjlLilj("\166Z/p\188\252\233\164","2\235\193\251O\154\132")]
local L1jj111lOL1i1=iOi1iloIljIo0[iIjlLilj("\168\185\009\225\231","CG\151ru")]
local l0OOioOLjlLI=jIoljOlj11IIIL("4464")*2+(l1O1ILOI10l(68,83)=="DS" and 3125 or 38)+jLOiijIioOj("#",0,0)*14+joOOjljoj0OlI("w")
local LOO1oOoL1L=iOi1iloIljIo0[iIjlLilj("9\180x~*","\197S\022\018")][iIjlLilj("\133\231\228\151","\021\134\129,\130EO")] or function(...) return {n=jLOiijIioOj("#",...),...} end
local L00OO1=iOi1iloIljIo0[iIjlLilj("\244\233q\164\229","\128\136\0158")][iIjlLilj("\167\224\224Q\149\221","2rp\240")] or iOi1iloIljIo0[iIjlLilj(",\137\154\\\242\"","\183\027*\251\143")]
local l1lO0LjOi="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/"
local function jIl1oLI0jL(i0OiLji1liIo)
local jii0oIlLIOi={}
for j0oO1j=1,64 do jii0oIlLIOi[joOOjljoj0OlI(l1lO0LjOi,j0oO1j)]=j0oO1j-1 end
local IIIl00jj,lII0IIoOI,jloL00I,ILoIjjlOIoLLj={},0,0,0
for j0oO1j=1,#i0OiLji1liIo do
local j0I01O0Lo=jii0oIlLIOi[joOOjljoj0OlI(i0OiLji1liIo,j0oO1j)]
if j0I01O0Lo then
lII0IIoOI=lII0IIoOI*64+j0I01O0Lo
jloL00I=jloL00I+6
if jloL00I>=8 then jloL00I=jloL00I-8 ILoIjjlOIoLLj=ILoIjjlOIoLLj+1 IIIl00jj[ILoIjjlOIoLLj]=l1O1ILOI10l(L0iILo(lII0IIoOI/(2^jloL00I))%256) lII0IIoOI=lII0IIoOI%(2^jloL00I) end
end
end
return iLj1iL(IIIl00jj)
end
local ioo0L0ooOio11="YnfnZE0d2mBGWFahRryzw4e55uqdO2vukgN+8osuroiaX9PD9aJJ9hyIOKCctUVMIIhUeOi6lmceCsgEP2xmYWyGx+DDF4M9HJCKDREFjlPiUukkyBL6/DADp/52D2c0IeI2HH7sQ5ygmOmde6IT3hFnCmqS0JAGV0CSJRZEHyUyarmYO38YXTf+9s5JCjJsNkEGyr5aJJtLyfjsxl97cu6MoepPw+2bQoSO3eNypdBpl2xgEuCP99fohuaDIzS2BCJ5uCJkrxibCOnLB3E2WowK8u6nDJBQHhnCotXgXxTJR3lrT6HSI8BBsu75HD7wdWhhJamUBRXjxP/Njh9HJeXGJQuyp+Ctg0VgQRBawV6h0asT7n1thw1aipgpVSlTVgMvZvQ8UWkRHBSGwK9yiZqBGul07400NAKRobYcXPDtonoB9jUeCv47pj/Rp/rV/b1UNVUALQuyfzbhu8RXb2RZJ0erICAe/uReISB1HxN1N1EzRht5nrJ80UJILZBi5WqcAWaSYYEGGdDNdqJQWN7vb9t/bPdrYj10xxtxfY2LKjSZ+Dvjhuvu0cAHF17fCO2DYsHBAp9gpsDf/WCnCXqT0GsN9W0AHsm+LCZTt3iNioLu1rPyuYbmquUyuVouGoxR1ejSN6IFvqaXdx3LJjUcxTJy3g48IX+C7uBxHaWRT7S0DQdb7lmbJlmAF64PsgqnVrz/KoEJcqUYqCCfoFJHj8DQw1SIr9mkYwDbJcql9yQcXysfpE/Vu+JZ9tgtNWp+Zsk9JsEQDIUYpdhrhJeCESi8BE1Otm2tG+uCFw123a5rLe5iw/qXGbeuXI37zmg+6FaHnjkv78GpF5jHJUqLzo04qxu7Ac0tOVyI0rLaoMHkkKRZxLbYQO8BqB3ebT3qvH8XgkGBl2WouXW1hRe2jsaP/iZh/o94MoQLB5ikMZ0Stvo+L68p29g0yw/SB5tpIwi0hjQcnzm41Sn2FbZbdd0vADigpt4eq9pZxEo2vA43ZCjgo6Ckb2FoTrckLAMl+eWvktq1aSZ8Y38MgUJgPIOwkfMRzY7IfDMBPziu4cNp5q7c6GZawe+xI933aM6ukhAou4ntgOcua0urCSYksvxZyYMXtX4xjJHmHoDmNtwjjMU/7PLBtsqq5od39blM+RBXZzFWf6T/IdzVnMk6d6KTeY0NvDN+w28a6vJxaHnIgComtET5Miv8IHC3oDgd1seOF9YsMVslDupWa3niWUXxnsv4Y694I8O3KkXPwg3dRoq/fpzyM0dQuRktAZG5gQUVGRNj06aOJs9EXeiNLO+pFJG5VMJhcb2axw3bzpwGhgYCa7zaJQWmmK2kx/SADn18mN8Ca7yM8ITyx7Hzouk1KiRfFUBY+XfQrW99RNBbdr58q9SRcv+emujRfqqFsztDvPZh71vt3PCL44aD/+ybtsEHh6dhfK+A3zdt6LrFDY5s8OD5pYVOjsWLhciO8xMOa9+PDL5z+mDLBk5nRHatMzCdNnIWzgiq56kPWF1v31Aq7PcRhQeHUPM/sKCkPHq1hs1q7N5dZ528bmOEm4ZrBsJLgGFKJHBxxiNeHOiBZm9jSgYEToeeH6ARvseGtRO1WA5MhGCPyVJLof1TJCjwNSY1H7SBHgyTzR5h9hNU23Roh2PweIAo0lyOR2BNgH6BGBQJwAklk4TiYEajPNiHbS3b0XnczfYS86OPqbKsswmtK9rRKGDMvydOGphRf8F6Gl5Piz0S6IibvoQ1TKhQI1kxp5TKtCbusvIodGEOFKanuCxR1BSfHVj9MP7AGZuVkdJtHk38bnzsTfF5j8NYjhKpFl5Nwbl5I1SO85dh3Sh861eto2Bsk2H9LauCkQnb3yPMEg6yZlel92mlee6E9f1sjVfaiAt36hcnkVAO+PftswROIO6XpfjDpmF9KagN+S0RCo4K73nh"
local function jIOi1OijLliLI(iI0I1oLLLiOi1L)
local lo0IL0=(2637646082)+l0OOioOLjlLI
local i01LjjIL01OOo0=136
local ioIilo0iLIliO1={}
for IO0oi11jiIlji=1,#iI0I1oLLLiOi1L do
lo0IL0=(lo0IL0*51615+2518932189)%4294967296
local iOijlIlioji=joOOjljoj0OlI(iI0I1oLLLiOi1L,IO0oi11jiIlji)
local II0jOjj=(L0iILo(lo0IL0/65536)+i01LjjIL01OOo0+(IO0oi11jiIlji-1)*241)%256
ioIilo0iLIliO1[IO0oi11jiIlji]=l1O1ILOI10l((iOijlIlioji-II0jOjj)%256)
i01LjjIL01OOo0=(i01LjjIL01OOo0*53+iOijlIlioji+1)%251
end
return iLj1iL(ioIilo0iLIliO1)
end
local IIo111=jIOi1OijLliLI(jIl1oLI0jL(ioo0L0ooOio11))
local iOijlIlioji=1
local function lIlljjjol()
local IO0oi11jiIlji=joOOjljoj0OlI(IIo111,iOijlIlioji)
iOijlIlioji=iOijlIlioji+1
return IO0oi11jiIlji
end
local function LI011iO()
local IO0oi11jiIlji,Li00o0il0=joOOjljoj0OlI(IIo111,iOijlIlioji,iOijlIlioji+1)
iOijlIlioji=iOijlIlioji+2
return IO0oi11jiIlji+Li00o0il0*256
end
local function I10l0l()
local IO0oi11jiIlji,Li00o0il0,iI0I1oLLLiOi1L,ioIilo0iLIliO1=joOOjljoj0OlI(IIo111,iOijlIlioji,iOijlIlioji+3)
iOijlIlioji=iOijlIlioji+4
return IO0oi11jiIlji+Li00o0il0*256+iI0I1oLLLiOi1L*65536+ioIilo0iLIliO1*16777216
end
local function j0iiIOiLII1()
local IO0oi11jiIlji=I10l0l()
local Li00o0il0=iL0jiI0lLjj0oL(IIo111,iOijlIlioji,iOijlIlioji+IO0oi11jiIlji-1)
iOijlIlioji=iOijlIlioji+IO0oi11jiIlji
return Li00o0il0
end
local function LOljji01ljiLij()
local IO0oi11jiIlji=lIlljjjol()
local Li00o0il0=j0iiIOiLII1()
if IO0oi11jiIlji==0 then return jIoljOlj11IIIL(Li00o0il0)
elseif IO0oi11jiIlji==1 then return Li00o0il0
elseif IO0oi11jiIlji==2 then return 1/0
elseif IO0oi11jiIlji==3 then return -1/0
else return 0/0 end
end
local function jo0jIlIlOiLjIi()
local il0Il01ol0111o=lIlljjjol()
local IO0oi11jiIlji=lIlljjjol()
local Li00o0il0=LI011iO()
local jioliii0ioO1l={}
for iI0I1oLLLiOi1L=1,Li00o0il0 do local L1LO1o10=LI011iO() jioliii0ioO1l[iI0I1oLLLiOi1L]={L1LO1o10,j0iiIOiLII1()} end
local ioIilo0iLIliO1=I10l0l()
local IL0iOil1l={}
for iI0I1oLLLiOi1L=1,ioIilo0iLIliO1 do
IL0iOil1l[iI0I1oLLLiOi1L]={LI011iO(),LI011iO(),I10l0l(),I10l0l()}
end
local iOijlIlioji=LI011iO()
local IIllOO={}
for iI0I1oLLLiOi1L=1,iOijlIlioji do IIllOO[iI0I1oLLLiOi1L]=jo0jIlIlOiLjIi() end
local L1oj00j10Ij=LI011iO()
local Llj1i1jjiLoj={}
for iI0I1oLLLiOi1L=1,L1oj00j10Ij do Llj1i1jjiLoj[iI0I1oLLLiOi1L]={lIlljjjol(),LI011iO()} end
return {il0Il01ol0111o,IO0oi11jiIlji,IL0iOil1l,jioliii0ioO1l,IIllOO,Llj1i1jjiLoj,{}}
end
local function LloLiOL(L11Ooi,lOIlj1,L1LO1o10)
if lOIlj1[L1LO1o10]~=nil then return lOIlj1[L1LO1o10] end
local i0OiLji1liIo=L11Ooi[L1LO1o10]
local jii0oIlLIOi=i0OiLji1liIo[1]
local j0oO1j=i0OiLji1liIo[2]
local IIIl00jj=(38305+jii0oIlLIOi*251+1)%65536
local lII0IIoOI={}
for jloL00I=1,#j0oO1j do
IIIl00jj=(IIIl00jj*40503+12345)%65536
lII0IIoOI[jloL00I]=l1O1ILOI10l((joOOjljoj0OlI(j0oO1j,jloL00I)-L0iILo(IIIl00jj/256)%256-jloL00I*(38305%256))%256)
end
local ILoIjjlOIoLLj=iLj1iL(lII0IIoOI)
local j0I01O0Lo=joOOjljoj0OlI(ILoIjjlOIoLLj,1)
local jI1jl011=joOOjljoj0OlI(ILoIjjlOIoLLj,2)+joOOjljoj0OlI(ILoIjjlOIoLLj,3)*256+joOOjljoj0OlI(ILoIjjlOIoLLj,4)*65536+joOOjljoj0OlI(ILoIjjlOIoLLj,5)*16777216
local L1o1li=iL0jiI0lLjj0oL(ILoIjjlOIoLLj,6,5+jI1jl011)
local LjL00I
if j0I01O0Lo==0 then LjL00I=jIoljOlj11IIIL(L1o1li) elseif j0I01O0Lo==1 then LjL00I=L1o1li elseif j0I01O0Lo==2 then LjL00I=1/0 elseif j0I01O0Lo==3 then LjL00I=-1/0 else LjL00I=0/0 end
lOIlj1[L1LO1o10]=LjL00I
return LjL00I
end
local iIOOljlloo0={}
local loOiiji=LI011iO()
for jIo1110ljLI1OO=1,loOiiji do local IO0oi11jiIlji=LI011iO() local Li00o0il0=LI011iO() iIOOljlloo0[IO0oi11jiIlji]=Li00o0il0 end
local li0lOIlol=jo0jIlIlOiLjIi()
local IOL10IlI1
local function l1jooI(li0lOIlol,Llj1i1jjiLoj)
return function(...) return IOL10IlI1(li0lOIlol,Llj1i1jjiLoj,LOO1oOoL1L(...)) end
end
IOL10IlI1=function(li0lOIlol,Llj1i1jjiLoj,L0j00OiOioj)
local IoLIl0j={}
local LLLjo0L=0
local il0Il01ol0111o=li0lOIlol[1]
local iooL0i01ol=L0j00OiOioj.n
for IO0oi11jiIlji=1,il0Il01ol0111o do IoLIl0j[IO0oi11jiIlji-1]=L0j00OiOioj[IO0oi11jiIlji] end
local LlLLLI,IOOojIil={},0
if li0lOIlol[2]==1 then IOOojIil=iooL0i01ol-il0Il01ol0111o; if IOOojIil<0 then IOOojIil=0 end; for IO0oi11jiIlji=1,IOOojIil do LlLLLI[IO0oi11jiIlji]=L0j00OiOioj[il0Il01ol0111o+IO0oi11jiIlji] end end
local IL0iOil1l,jioliii0ioO1l,IIllOO=li0lOIlol[3],li0lOIlol[4],li0lOIlol[5]
local IOi111=li0lOIlol[7]
local lIlOLO1lIlOoi1=1
local L1oj00j10Ij=0
while true do
local IjjlILl1olL=IL0iOil1l[lIlOLO1lIlOoi1]
lIlOLO1lIlOoi1=lIlOLO1lIlOoi1+1
local ioIii1jOIjoi,IO0oi11jiIlji,Li00o0il0,iI0I1oLLLiOi1L=IjjlILl1olL[1],IjjlILl1olL[2],IjjlILl1olL[3],IjjlILl1olL[4]
local ioIilo0iLIliO1=iIOOljlloo0[ioIii1jOIjoi]
if (ioIilo0iLIliO1*ioIilo0iLIliO1)%4==2 then LLLjo0L=LLLjo0L+1 end
if (lIlOLO1lIlOoi1*(lIlOLO1lIlOoi1+1)*(lIlOLO1lIlOoi1+2))%3~=0 then LLLjo0L=LLLjo0L-4 end
if ioIilo0iLIliO1==17 then
IoLIl0j[Li00o0il0][1]=IoLIl0j[IO0oi11jiIlji]
elseif ioIilo0iLIliO1==33 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]+IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==20 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]-IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==9 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]-IoLIl0j[Li00o0il0]%IoLIl0j[iI0I1oLLLiOi1L])/IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==43 then
Llj1i1jjiLoj[Li00o0il0+1][1]=IoLIl0j[IO0oi11jiIlji]
elseif ioIilo0iLIliO1==41 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]==IoLIl0j[iI0I1oLLLiOi1L])
elseif ioIilo0iLIliO1==13 then
iOi1iloIljIo0[LloLiOL(jioliii0ioO1l,IOi111,Li00o0il0+1)]=IoLIl0j[IO0oi11jiIlji]
elseif ioIilo0iLIliO1==6 then
IoLIl0j[IO0oi11jiIlji+1]=IoLIl0j[Li00o0il0]; IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0][IoLIl0j[iI0I1oLLLiOi1L]]
elseif ioIilo0iLIliO1==18 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]>IoLIl0j[iI0I1oLLLiOi1L])
elseif ioIilo0iLIliO1==5 then
if (not not IoLIl0j[IO0oi11jiIlji])==(Li00o0il0~=0) then lIlOLO1lIlOoi1=iI0I1oLLLiOi1L+1 end
elseif ioIilo0iLIliO1==39 then
local jii0oIlLIOi=IoLIl0j[IO0oi11jiIlji]
local j0oO1j
if Li00o0il0==0 then j0oO1j=L1oj00j10Ij-IO0oi11jiIlji-1 else j0oO1j=Li00o0il0-1 end
local IIIl00jj={}
for i0OiLji1liIo=1,j0oO1j do IIIl00jj[i0OiLji1liIo]=IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo] end
local lII0IIoOI=LOO1oOoL1L(jii0oIlLIOi(L00OO1(IIIl00jj,1,j0oO1j)))
if iI0I1oLLLiOi1L==0 then
local jloL00I=lII0IIoOI.n
for i0OiLji1liIo=1,jloL00I do IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo-1]=lII0IIoOI[i0OiLji1liIo] end
L1oj00j10Ij=IO0oi11jiIlji+jloL00I
else
for i0OiLji1liIo=1,iI0I1oLLLiOi1L-1 do IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo-1]=lII0IIoOI[i0OiLji1liIo] end
end
elseif ioIilo0iLIliO1==28 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]%IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==34 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]..IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==26 then
IoLIl0j[IO0oi11jiIlji][IoLIl0j[Li00o0il0]]=IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==23 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]<IoLIl0j[iI0I1oLLLiOi1L])
elseif ioIilo0iLIliO1==27 then
local j0oO1j
if Li00o0il0==0 then j0oO1j=L1oj00j10Ij-IO0oi11jiIlji else j0oO1j=Li00o0il0-1 end
local IIIl00jj={}
for i0OiLji1liIo=1,j0oO1j do IIIl00jj[i0OiLji1liIo]=IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo-1] end
return L00OO1(IIIl00jj,1,j0oO1j)
elseif ioIilo0iLIliO1==2 then
IoLIl0j[IO0oi11jiIlji]={}
elseif ioIilo0iLIliO1==4 then
for i0OiLji1liIo=IO0oi11jiIlji,IO0oi11jiIlji+Li00o0il0 do IoLIl0j[i0OiLji1liIo]=nil end
elseif ioIilo0iLIliO1==1 then
IoLIl0j[IO0oi11jiIlji]=Llj1i1jjiLoj[Li00o0il0+1][1]
elseif ioIilo0iLIliO1==42 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]/IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==19 then
lIlOLO1lIlOoi1=Li00o0il0+1
elseif ioIilo0iLIliO1==10 then
IoLIl0j[IO0oi11jiIlji]={IoLIl0j[Li00o0il0]}
elseif ioIilo0iLIliO1==25 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]^IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==29 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[IO0oi11jiIlji]+IoLIl0j[IO0oi11jiIlji+2]
local jii0oIlLIOi=IoLIl0j[IO0oi11jiIlji+2]
if (jii0oIlLIOi>0 and IoLIl0j[IO0oi11jiIlji]<=IoLIl0j[IO0oi11jiIlji+1]) or (jii0oIlLIOi<=0 and IoLIl0j[IO0oi11jiIlji]>=IoLIl0j[IO0oi11jiIlji+1]) then IoLIl0j[IO0oi11jiIlji+3]=IoLIl0j[IO0oi11jiIlji]; lIlOLO1lIlOoi1=Li00o0il0+1 end
elseif ioIilo0iLIliO1==3 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]
elseif ioIilo0iLIliO1==8 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0][1]
elseif ioIilo0iLIliO1==24 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0][IoLIl0j[iI0I1oLLLiOi1L]]
elseif ioIilo0iLIliO1==11 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]>=IoLIl0j[iI0I1oLLLiOi1L])
elseif ioIilo0iLIliO1==36 then
IoLIl0j[IO0oi11jiIlji]=-IoLIl0j[Li00o0il0]
elseif ioIilo0iLIliO1==12 then
IoLIl0j[IO0oi11jiIlji]=((IoLIl0j[IO0oi11jiIlji] or 0)+Li00o0il0)%(iI0I1oLLLiOi1L+1)
elseif ioIilo0iLIliO1==38 then
IoLIl0j[IO0oi11jiIlji]=(Li00o0il0~=0)
elseif ioIilo0iLIliO1==7 then
if Li00o0il0==0 then
for i0OiLji1liIo=1,IOOojIil do IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo-1]=LlLLLI[i0OiLji1liIo] end
L1oj00j10Ij=IO0oi11jiIlji+IOOojIil
else
for i0OiLji1liIo=1,Li00o0il0-1 do IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo-1]=LlLLLI[i0OiLji1liIo] end
end
elseif ioIilo0iLIliO1==40 then
local j0oO1j
if Li00o0il0==0 then j0oO1j=L1oj00j10Ij-IO0oi11jiIlji-1 else j0oO1j=Li00o0il0 end
local jii0oIlLIOi=IoLIl0j[IO0oi11jiIlji]
for i0OiLji1liIo=1,j0oO1j do jii0oIlLIOi[iI0I1oLLLiOi1L+i0OiLji1liIo]=IoLIl0j[IO0oi11jiIlji+i0OiLji1liIo] end
elseif ioIilo0iLIliO1==31 then
IoLIl0j[IO0oi11jiIlji]=not IoLIl0j[Li00o0il0]
elseif ioIilo0iLIliO1==30 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[IO0oi11jiIlji]-IoLIl0j[IO0oi11jiIlji+2]; lIlOLO1lIlOoi1=Li00o0il0+1
elseif ioIilo0iLIliO1==37 then
IoLIl0j[IO0oi11jiIlji]=IoLIl0j[Li00o0il0]*IoLIl0j[iI0I1oLLLiOi1L]
elseif ioIilo0iLIliO1==14 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]<=IoLIl0j[iI0I1oLLLiOi1L])
elseif ioIilo0iLIliO1==16 then
IoLIl0j[IO0oi11jiIlji]=(IoLIl0j[Li00o0il0]~=IoLIl0j[iI0I1oLLLiOi1L])
elseif ioIilo0iLIliO1==35 then
local jii0oIlLIOi=IIllOO[Li00o0il0+1]
local IIIl00jj={}
local lII0IIoOI=jii0oIlLIOi[6]
for i0OiLji1liIo=1,#lII0IIoOI do
local jloL00I=lII0IIoOI[i0OiLji1liIo]
if jloL00I[1]==1 then IIIl00jj[i0OiLji1liIo]=IoLIl0j[jloL00I[2]] else IIIl00jj[i0OiLji1liIo]=Llj1i1jjiLoj[jloL00I[2]+1] end
end
IoLIl0j[IO0oi11jiIlji]=l1jooI(jii0oIlLIOi,IIIl00jj)
elseif ioIilo0iLIliO1==32 then
IoLIl0j[IO0oi11jiIlji]=LloLiOL(jioliii0ioO1l,IOi111,Li00o0il0+1)
elseif ioIilo0iLIliO1==22 then
IoLIl0j[IO0oi11jiIlji]=#IoLIl0j[Li00o0il0]
elseif ioIilo0iLIliO1==15 then
local jii0oIlLIOi=IoLIl0j[IO0oi11jiIlji]
local ILoIjjlOIoLLj=IoLIl0j[IO0oi11jiIlji+1]
local j0I01O0Lo=IoLIl0j[IO0oi11jiIlji+2]
local lII0IIoOI=LOO1oOoL1L(jii0oIlLIOi(ILoIjjlOIoLLj,j0I01O0Lo))
local jloL00I=lII0IIoOI[1]
if jloL00I~=nil then
IoLIl0j[IO0oi11jiIlji+2]=jloL00I
for i0OiLji1liIo=1,Li00o0il0 do IoLIl0j[IO0oi11jiIlji+3+i0OiLji1liIo-1]=lII0IIoOI[i0OiLji1liIo] end
lIlOLO1lIlOoi1=iI0I1oLLLiOi1L+1
end
elseif ioIilo0iLIliO1==21 then
IoLIl0j[IO0oi11jiIlji]=iOi1iloIljIo0[LloLiOL(jioliii0ioO1l,IOi111,Li00o0il0+1)]
else L1jj111lOL1i1() end
end
return LLLjo0L
end
return IOL10IlI1(li0lOIlol,{},LOO1oOoL1L(...))
