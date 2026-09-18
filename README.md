-- hide.lat / lite / 1cb6bcc52cdd
local IilI0O=(getfenv and getfenv(1)) or _ENV or _G
local llIjOiL01l10,llIio11l1oL1Il=string.byte,string.char
local function jL1III1(IoiooijILoIiO,l1O0lI)
local Io10iiL00=""
local iIoIoli0Il=#l1O0lI
for Illj1o=1,#IoiooijILoIiO do Io10iiL00=Io10iiL00..llIio11l1oL1Il((llIjOiL01l10(IoiooijILoIiO,Illj1o)-llIjOiL01l10(l1O0lI,(Illj1o-1)%iIoIoli0Il+1))%256) end
return Io10iiL00
end
local Lo1ijoo0l=IilI0O[jL1III1("\r\173_\009bu","\154H\243\164\255\001")]
local jOLLjjiLij11=IilI0O[jL1III1("\162\138\232\250`\181","/\022v\145\242N\232")][jL1III1("\224^t","m\233\018")]
local L1oL1O1LOILjo=IilI0O[jL1III1("\003P\157\162\244","\143\239;6")][jL1III1("\249\007'\155\247!","\150\152\1858\150\173")]
local jo0LOLo1j1IO1=IilI0O[jL1III1("[$U\213","\238\195\225mc[")][jL1III1("\175\160\149d}","I4&\245\011")]
local jlijilI=IilI0O[jL1III1("\193\003]\028\186\246T\025","M\148\239\167")]
local Io1LijiIj0LOI=IilI0O[jL1III1("l\222\251v\222","\007l\137")]
local iOljOIO1lOLI=(llIio11l1oL1Il(75,86)=="KV" and 4337 or 32)+jlijilI("4134")*2+Lo1ijoo0l("#",0,0)*4+llIjOiL01l10(",")
local iji1ijiOl=IilI0O[jL1III1("\n\215\191V\191","\150v]\234Z\\")][jL1III1("\020\020T1","\164\179\241\198\239*")] or function(...) return {n=Lo1ijoo0l("#",...),...} end
local joii1Ij=IilI0O[jL1III1("\020N\194w\150","\160\237`\0111")][jL1III1("\240!z\220\022u","{\179\n")] or IilI0O[jL1III1("\026\128\137OF\235","\165\018\025\238\227\128")]
local LOIIlL0IIjiij="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/"
local function j0Olo0il0Ll1(jIoLo0Ooj)
local LL11I0L={}
for ijo1ilo1=1,64 do LL11I0L[llIjOiL01l10(LOIIlL0IIjiij,ijo1ilo1)]=ijo1ilo1-1 end
local io0iIlj1O,IIiOII0,LL1LO1i0il1O,iioOIo1II1Lo={},0,0,0
for ijo1ilo1=1,#jIoLo0Ooj do
local ijioLjLliIi=LL11I0L[llIjOiL01l10(jIoLo0Ooj,ijo1ilo1)]
if ijioLjLliIi then
IIiOII0=IIiOII0*64+ijioLjLliIi
LL1LO1i0il1O=LL1LO1i0il1O+6
if LL1LO1i0il1O>=8 then LL1LO1i0il1O=LL1LO1i0il1O-8 iioOIo1II1Lo=iioOIo1II1Lo+1 io0iIlj1O[iioOIo1II1Lo]=llIio11l1oL1Il(jo0LOLo1j1IO1(IIiOII0/(2^LL1LO1i0il1O))%256) IIiOII0=IIiOII0%(2^LL1LO1i0il1O) end
end
end
return L1oL1O1LOILjo(io0iIlj1O)
end
local L0oLlIo1Lo0="PdYU50lxS8RdEjvwL1VsbhywDKbARVv/TPkBkq6y+3XxO2MEy9hjFCwblbKJF6ODvWQO/LbJRe61O4N/P8QyO1lTpLn8Y7cuTHKxfIlE1MlxXrPElZXc9bzV6QpsnI7E+7fvotHvVuIX+MNdFcTaDdcTx2FQRox5iBkRUa8PDq4jP0DXU0yp/aqZ/j40Ko6jNIEuXEj9v2l2i21b9IJ3z1TVQaE62L8YjPQK+ygZYOSptPmzfHa1/MyTcwNXifbRtRpVldWWwc7dy30zRHWiA0Pmzb2njVlYpgfA86pR8ubaDRdzSsXCP6ZL5tHYnRmAZk7nTQbt7flH6HpRfLcvhQ3J8DY9H+HdfWlrB7vvJG9YQGVsYspv5wzAI3X6oxNb2Gg/36D8vqD5+jDE38POsL8MfQVeQxaJQxD2B9dBUc1giV2PjA9g0lsi9OnwZ6gskPDHkk00BmqGxNkanu/L5pT0z8raiOt03yNjm+iVLvk6UYkPDwJc8hnxNKx7wbuQ3BjSkGZDViwY8Z6FA6/vwqFuyjSmpBUEnFuI9NGhfMYQzVqP0vq3AW5PpigO72H51lvxkQ7wrBKruC/xnryhxyz8sSwZH3rsV38tkw9MulgRgojQ07Y3N4A29131momD5wSxsgue3aOS8AAy8gp/e+l1JVGlNROZrRsfdIbfSJm1x8uB+6PQlapZdvlJlv/vuVzn5wMD4tYq9Yiu5aS+ylq3rRh8bDBCij3AUdi/N1h3UTWOTq3L83aHGcSptew7l0UcWxFNVssm6XDZbmFnwU3D/Wh+81DhDZCvrXRijYE4dNq7949tuJ46jdWtgM0L4OYjZysfnUvIKB5yIxIjzj0hc+B6JIqLOgi5Xt4sPp14B+5pZnw5QBEjjCPpyWFUYcyJUwAgFcdAY4BJr+8bRD38IJmEVJwq2o7LG3SpFvRygM5nslm4W0q9FD3KC//MGg4k3SH3dKOIz0yRC4J8loPg0EMkYkWMYWNePgioyaSYlow75orG/JPKhViWs7uMRQt1/m7EhMiPkt8m0A6HIByeXc1aWNSAAMuFhkUDfdJu8XHYyyfWfYmBQPsi+I/NgBYUrqgzfQbdM/yLsCFfKVnMWAwiZ9ODpTRCoMbNbyItXMAbl/Hr8aqV9YSqmoiEK7s3TPQn6A8IsmBaiTIyXrEBcZYeUYYPhiSmKS1WJHN11Hn2M6x7DOhI2RmJOQ9YY2A7C2wE86vD6Ucy3e0NvjmF8UlrG4aFeYBbtxhr6DApIk1qHBoZpjukxIt8606YVee0dJCnCKJGMZIlxXO1mVTR7qWvAh1YtlZZy6arRKT8xe0eJEZppsn3iFdJkK2pXQ+iWT+kiNOjb44k9aJOd+LZFcYZtSjmjeEGpNkv5q4m9/RkvQlGF689ML+oZPfu1UWNWCtgoARdLCj2Akb7G/b8pJRYWKK7bm0rLy2ghdp+oYyU0lnzDYqg+PsqwSeFVKNH3cf3wL1bCPWSdG1KBGsubY7y2Y7hZhVmHAIPD6W0/rNkXzuf3QpldlUo7uOosQ3jFGSvWN36t7IR+rHGIFHBaoEm2I7/avdBskgsi4hHvYwo+QbR3ZT12GwpLTqPNKgGiaCpxmJV/27n2fT94HltGlfQpbCsxMi7R1IUszbwq+aN8t1vQUC8g1/97dJM1gbETLHKngMSwtut9hf6FCfpYzZtV2FelDnwOlbwRbAHOafU9RoYem8RKAQekwyAaUlICDMFUErmob8pU4AoT5tdvFyVITcr//eQ92wyqihyFVE69wpGAiGskx83kLXLYj0fi/sNa2mCs/zdbW2cDUf2vZIPDATHPzkgQiv8I92pXvBkjurRcGfJADiMHfEdz8MW1QIUa28Oc8uTVMSPlsSM0PTcGXqwVe2xQi73McComC4Am5chyNDN4r/I7pjTTyTiEsgEbaRjtSzlmbp4OfDem0oXS2+9QcNVboZYIofqBX1VKYC0le7CfbnoB0GmFJ+zS5bHakneyFHvIZEleglh10Iwh4cKfjrk4bjFuHmX6gsFAmVNSGEFigrZP3A/sypfTTXDGZGD0UVOk33FgYwRqTIWee7uW+Oxvlw+W5vfTWUaNK46LCnjTti6QvchPDASTkhK06dTGCRYtQTENdBQouVqUVeFhXHYaWN9X5vSiWGTlazthH4xHs9f2NNlbE2PsXPO8awglYlzBIssbHWpZ3IXbbiJMml7EYOoR2iXq0anPr5WLGjGJegsc9G6Fvv87DS6S3GZ0MixVzem5t3yQjooYV/8ZsNXSXSg0qZvk8mV1OpBoPcW+0wa13aUvArqERqmd7k97MTdJXpiqHzNUKIftpEXBCjsQVcHWyKTevfo7gu/cHRFSQGhxyuNvHH4RrCBvgMYw+44nojmnF1NVQklK6VNGpWhx+liULwqICqdAqHJuYFznXXib1kCNIKYTy0fU4aZ1Z/0BEBEeO5AKZ30XLiJYLy54n5uOhde+1XTWqRAQNvL9qPnQzVgc9NqQtaEYmwzOYKJf4CaGpwzH5ZNfTIjiyqB/XekaL6lP0Yih0Vd7xeb5u7QZvj/ug/swTMG6NLnqNsxwS00rhxuXAwgTM8jJ7qDs8keM5LWkDPNkyjMnm2Zungl9TYvFuO7zYIUm48WWDwYxXWr8XuDyxCXPTaYKY0+bVF14mNrTOaEyGxW3yAwjgmXZvI0HGcTf7Z7QtohlM6L6h+MSCJfwpBy97b+zylUUZWDc2CJdDydo8KsRBCwxZ6Pc8gMTu7qlgMQX/W95FEy7NvaKdpOgXtsw0QtyftdTLdmqb64Xi9taWSe0/lme2BmJBwI3u4NK7eH9F8jNZFQo7VP6x+S1c6BrInWiZnYSztV6i5ckAKskG+SIC7BosmBPmJ1x8Sz0Pw+2A9Uw3MivRa/QY6HD2Nk2x/qU2Hml+YCIJGNVSX652b5AybZpaIQpNfyQqdZHa5LgmVoueilOuZlb7HuuogHW3NzFONqpJmzrzo13AVFpEvn6qCNeWs7KP8C5S2d9qDDzxHqglvxGJJLXzNTkwJV1pRz4N+eLXy85Rlmc28AQVcekDsPxg8yDBXcF+XwkSVm1Fv69wTD0kME095wPBpjvy2nJo5zRB7VMXKXExEKsdy0AGIlE7CkaqfUne+gqbTIy2OG0VQ5fWnJ5ZBYytaJmgyewI99oiaWr3aQ0Oig7M8bmZtsr0zJ8keLfkCu8IkTcHBIf6WTsg2MtK6JamK7sxdyAZ0UzJS+rFXqQotjRQSTxoABksiYx9h9zR7BPnnW8iRDsfCH7OmfZISVw/C6ooXk/CGuydoEcJykUC+twFpaUvSRBn8Id6nt5lT2+TzvWPTl3ZXnTU/Lcom0MahNBKEhB+dckwLs0N5jR0DdgOGUEskBt4YhH7aj720n/FGsD3/Ux2L/f1ippmJifEmSqlV3a/ho+uvLXQ7fJzlu+8SLyqpFWMk92r6gnuojw2ue93BAW9kEk9bekL5PGjDSP2MZAhbu6RXUuxhzfvxIB4LzwEQuxCq09WP5Wb2lEEx4/cEShoONKdxmhbzTW1EFHUSBT+JLeftXueP84VOfnRrrBqwz1TY7fF2MHO2kpN6IQO2n0PtVFl6ZPmBMqn2lg8BLXqlIT841oEY03rFvSvOgZCmZU8+x+kGvoCVKHG13MhULgwleFdq9q97mYTGyD/OL1Tnvs3PtPQ8XvNBcnstwOY1ixqWvxUEmds5X5A7BjdPk8CS5Nw8yeVIjvBKoPiB6coTapZ6AcUXHm/O5nLdsVfZaNBL7YcjtR4q4byaPIDUaG16Z25R0WqFdeNIza8KwquwwZwg9ojkXSvxvSyBcdsaAu7cz4TwYnVJ2rhRg8GCRH8maiIWEEN/GRf6GHqSgalny67ds93rg6i7iSZmx2pCHV6i1XiE9BlPOOk0t2gr+XCmsuzReQqojnTEHx8igRcgKTjzM4VjJYrvr+n5nkiq+d9grYjg+pz6ebYvlMEw7ow6iXz4nEDl4N7evhrFSElytJu6tLMcm+iLzbDlERo3KGgWwF/OrCEU5UymgKG7hvC49g/M26AFxvpXwJvEp1atql2tVDPAHqu0rhp8/nrwv/rhYDitFqmuRi0AIRSwF0YYWTmLZuN8VONXyUMRDhi/W7f1t9wnDnFGamc4a3FfhZWlhQMThASO9gqdmn6xh5270aVjUFkqepHlylekdTTGu5p3N0eNCj2DHyf1dO6/RYsXWdfWH9CMVRR+Lokg5BMXP+AKg8WQDIj+XPgklKUXzrc5WoT4MDW7WDkfoJdDhh9CJ3YjGeSvEnaqDeSG2YFRxZB+G1Kw0N+WSYCAbtdeOcHRGYsXDzlCfGB+BN8/Op9WVrqA/fTKeiyDxUX/1t+ZCye0RDCfG1B2lemRhAtznPzJT8zeMwZAB6dUSdU4sPFDOrraZif5ETSC6azZqc7BcKKo//mvnM1NnzKU6D+MKE+5kGd+aFTnsVdypIt9MmghLzd6r97bm58eOfod0xiKcDY0/xe+wnPOJPgB5lnwk+7MrRCaW8EkdbXs3Aau3+Yupkl3jt3LrIw4F0ofBFWc2aopgZtqWYaMC+IzujwUYwFUetBERcswzjvMry/QhTevCVX7/PzerABpqTZIIYZiZKsY6c8PQj5VltJEcICwhKpRSCEsGZhO+PDUfSaJdPR1ZGIiT8d1el9RdvsrYtN1OO8sL+g6kmw71lpo6GawqE4t+5WzY4MRdZytR7Gtg2RLAG6X6Y6qPL3LZefts2+TWgEkKrOsIRZEpUVy/6qyn2/B4E8ZciAG03PU4vVk5ZK0o493Y97qoTTnJmCbUr6pyOdRk3EboR6QrS+6BuJGBm/FyoYIDdz16OPeseD4qJ2SkwDDxtfG2SDUZSsuTgJrfkarncR2L72nhH3Ryq8qkA7breHkeWsngAuMp06MvD2+hmrXRrS5Q3HeTs5H7xH9Rnf/k5xs934ClxWfjZqyG9gn+LYUaTlhp/ay5GdaefYuZ/6lHveFqhRyb89DV6Gu1tnggd6iexfz78T/sXrSbIrv8lRCTw36vFTw6RbXHBoY0J/GLHh65bs4wSMTnObM5zoGLx3HUt4k7/drY5Zt7VMDZPVoPUnwB3QNBx1h/cyXuBehocqhMSsOXIk7fETU41paTokwdZGIQgMUgDoUWHRhOvd3zWOrBisfNL3FKvrl8hajef/QhuVGKN8wlkyFuKT+4FSA80zD4PAwY6Gk3QKZyOhCZPPxe7XMHgSicD/k5Mj8dONeEfyQv9mcKAs0PpBHOxQANnLIMik23OgHlU2cMslymofNKEnfVig99o5j20rETXen40Iy37YNLWjdbkXpljobnLRyRL37ju81RUaXfR0oEO74234DyY9y4l+U0Lu+joHPh/GHQqkcLEzcGJ0uwHIZ6PqhqrCeLyfeeC8fPEeyQERQJUT4QHIn7yhv4r5gO3148O7Q5gmAdr+IYJDNIMHi4jLr7Bc3nrFVYNU8ED6lZDCn6FlI+sQDCbT5yjN3p8gHWEqgibFFDnf+gPYBsDKDOylpEztNFpxu+9/wH/aCoe/NCBGSSaAN2Z/HJ30kVlKv4horCeCUmcOcSfQBLkx6q53ZR7lQoeG+qdwMN1XWBy6Cg0cIpWjC2ez1aN9al4SnjOWcrJcF/pfiEgefa1grQZ88i8MEb3XmM3lHjVT0hyS8uqthQNJAFEvej+9u3uVrAhPmVhtCL0xW1oAgfiyjezSr2h5sPrBTuTC4Qxgjo987Bf+A9ZdDYth26DpgJQgoaHmnaVXdiUR8kT+/4zt4PmOu8s+HZwB9lK21Jl//zU6uMlFPszC2f4osrQztdozl9r+WdA2o3Rervjo8i+ACCxkmVeUo7K5cY/zrt9jv7Q7vj2+H2pae7gya2FnnVO8NYs91f1lkeqk4T/GgOCHKZMJg8+EPYwnOsmWNZlQ+9VQSVJ1DgbFWklc4QBX2zLLb0xdJE96w8iTdn/SbG54UYZkM6OFpm8iG5Y5loLR6ru+HtsWTUijrk/spN/+lVVvGoJPdVShACslA6Ith5qCxm8Tz95PHO+Csme26giTsCa/VW4xy4hibMG4ozzblnSqDfBjura/PHTwA1NlLoSFAGKq7bw8vLarU61yekJxej+c/ioq/m6xnXHj9FJT0O9xKu+Bd0+Jvw9p0StTQMuAp+lCqGAHmdOSZlcaGF3vA2ieluXZpDD02gJXiGDaAr3gC+bYANeAN3WK/yS5DuqChip+kRhDZbk4GSHp9GanoGvnXmZv7eikpT7x0tE6w0GGFPv4euCyA8N5L1mMGK+Kq/q66kIG+g3e1//QfT8131ZHaR5EU/foKFt6nDLzyZl9GnbBLxfe7rVxpoSAcetGPs7nZgORn1XGleBAGqE6pi8S55b6GI8nJvYjHsLTYiw73okqiUgxjTuwpViVwrX0m47eO4jp7k+oCsv79jv9R++RNBVCG0uXJfB4Z3iQyRJCOkOvIFjYxwo2OoVniEhF5Uqm9/8QNQ3HYR3e/g0LSjKpFznEW0X/UyI8k0y/Sa+G4JV6woXTtVGUnaKwCa+B04dLqo+WijY9ec8F9RdwUIH1G9e72Q82IZx+pyJd4c6nB0lephGg1BimDz6fajSKT+BNd/Z3Xo3EBhGju6r75mVENHUucWclW9SkbKh0r5xFGevaYWhBQ2BIkXNI4UEeepYtBBpctmaS+T65oOwkdcymrQ3f2kN1E4oB13pdBNjiJujYv/YxHbcJikrgSvtKMGVlO9EofDSrSQrkX8D9skq6S0GRmgeKhrcFgxnExFesX9prorOR9SFqyddswTugqxDy+JUIX1U+3+3DEPuA+K8yFUNU2kFQo7ImiDJmtX6s4TL7NXX2x2fLgsviKR/J+JQX3yAmxFK3u4pnrFbHDQLlMMJJIa0xmiWBvtH/0z/GzAd2pVVn/JWBlgL1udyhyLYoOT5bYcsLFcJuXlFdONZ5GwNsuR5DPkfhvQSHiT528AWGGg4Z8qHCHRDzqG6saatCxxqXps5FL1QFf7YY6AKiuFmZJbPk3lcqAg5XtZ+DK6DBkEb1ZHnRi6L4wK6SgUsbVuKvUi+GO0LJBKBTqQxjh+1M3H5AJ7NX4Vpw7DuNxk/7TglQDy8CXmHYvbE3R+Yb6E4193VxLW2gcfRxELBWYIa2hsIfciOKnZ7ecsUO2+GX6a4/fzTZbrKgfKIQTAsBYEXkrtmXGTVheUFqY9lWIOs/PtnIPK+jPO2TlkxVdBJ8WEPWujTHN+u2kwdejPWJoi8tvmtx5ijGK7e8rH/aB4uxnpQUUmX2GtU3lgg81Rjbgd0E8FYkHdaUXV8Ap0lt7NftmapsHugry2AsmmrYGno8IuXxlVePX/eAo1xYfYTTXJdQytpoiIu4xoJF5GX0bHyaNEXOqJu9K5f7x0mllonDTjzGIFl0ujsOl5QS+IZtZKxcSZ5PTLDI0QXUFnCy2dqVzl4QV/Akge26o6wc0Nege2/QVaeyV/TFqGt/5xThRa7efoULzzMQ2X7jz6LKlkUShhC2CrvmhLrMR3zIrVBl+1/q+EJ/QTS3xoNVPASeQM+A14fQq3IsSMPdeRM67KZHxKLe9kNaW5rs/r4twtnb94iP++Vbv+ZTCyR6DzMIe/S2+r6W//D8M5jN+tmjmMEJsza+GqjjYeo2Pwzga3AXBppbpWcMa+9n/UvBM78kv2yHcsvNRKYhv1PzXFZZ55sqTr51BgrTvKPH2Z0heynjZqhZGOoqLnALIEKIRfjFpIicMF6Q3D3l9MAZwDIbyFWnKOsB2GDdy1Fo6Ca2mkVxOaNYGEBVGNjKutBLq5M411bF3yiu0UbrS9KKajZqeB3AEI1T7RM2tmoU/yOOej4aXwvHIRsd4emQ6Ic6B+1sBQ5EIg/XmrL2eKmlfmjGoKHpPfYYRgtd5lVqi9tDbLVfhpxL29EcmjPNcew3cvY4ZEGeclvvXiX3rGavss0v2TMpXgl2y1w5F24gLBrS+Yw/9646j8cSlVzkUUCTliW37FlgnFYWxd9+Alef0SBF6IFxl56wit0+AeN6nOJC6svRJZTnme0zKhMuQxU3GWyA1+7wsMMmirDTka6ZM70FeJiD3P5hQF9nSgsUVIbmU8Fg3exNBZzD1eriHX8ovN1lbX04fBHsYZYNH9P9LYAAcWyx1KUWMdk49+uecwx1YF9kVlfuyGfR+3eyUl2EgyqTXCiND4uky1Bt++Mnh9I4+c5hZjBNvQ+bBQ2F8qZ3dJ8wFFiaYVwtnjH1z1CbOxao1rBGk4W+KJYaFdX2X2HusEsjdNIwGj2kpbYMkymrYBTwLmfIzSWc2gH5b1B5S7FKoDClyC4uLLgu/oKiqhYLIJ83XzjYjGCJMbPJGJcUjd1C/GU9+TXJbJ3bL1WWM9V+3YmfoQRqB7MJYRiTuQpMaXIfYOabJj76jIqRNMUldk+K2S/avsXStr0PI+KmEPlDq65nSpI9jMUWBYxTV7RLHu51k6osUjnUpDADZ+7P9cLeB7O5GjAFsHaDhyK1TgbPV57GokDOUqu5FkDmfbuEZJyxjTMmnmuGBLeev1Mj9rooP9kd1JJk/j6qoM2VLDi2vXp1/S+xavBwEaSwkI0dK/eJIE/M9Fcq21+QIUUPHWviWTDwtDmuWeu6NNTfLCIjTkUFQKDDaa0ShMUD9Edtv1jYYfBmLoY/KIWNa+afMKoCBVTTnLsQxJc/DBOY2XPdehdX/zs6BekyvM8W8hQUnhYNcFNDfikf6Ulnn8KoVDV28VX21LaQeO0gvqcSmsXGTINE0daDXdRKw47oEkajbAVqcwmr63G+0PkKa6eXvKWsQbKNQC7/UqSLNHxrnVnmysMkCP6+T0JH+i7mTB6cZx044qoLwUuJ3pEMYuOP+W+2Q69miobvN1S1xJKUXCj9+DbjxMJNfy2UYza61qGe82Xz+gYdvose0UxBr2rrE5AvNJRpnJVJAjUfSheRVjoWaFNzqQoWJVQzmaVkmaUzKSB9DBv+hX4k2A1/XdtKEbXc3rSPPsSRj/E5ESnOScK1sX13unaA73HN4TT7tL1XVU0FJ8u3HmyPVgQH55sDpvGfNKWODeKGuMzvzyKlipFtW6j9LRE3/IZHpu1uzdpj1X5mRkN3jmosjvjtOTUf0tYwiPuRrmMeX94lY3MGHQOKE8vO2PJs+CDy0HMMUPbcLiD2qScI+kpHzkw4zT2MaC5MC/r4q95jZ0h+Uj0ltbtiv8g98cvLz8D8e9QmiVxexPVa7wGAiWHL3gmoIbKyFQGj2nC4CKpYsHgPbOuS5wc+dYrcVyBTvXIuNQ0UqVxRCC1BQHruxyqalENZqVI1RV8oHxCWSycxCb6QysNORZ/38t7Y47mz/lPsa1aHQOQz2wBZ1JbtYbFIZtnGSZ8BODJzU6MC26Plwxg3COjs1Z8nMUP9PrRMacmmNClWzo5FXut0vYoIxKeCvTrakVJTvNkXvANP3415PiVvZBIZCsFGKjuZsRCPK7FFlbJ5/AOevNDJruE9sJPgKKezElR8go3UCdwqDt3Vu4ati87AQFIrT/u9Sb71hxq3y6nC+OyhGWHJDnLPs0BLmF5QZP9+RUb+JdTtWaRvbNKyFGvfgrUq149bKUV2eRtuAySVZM2zMP1db1Ue5VBI1+i0tSoz88DfN4DksrwQkXw5gXFlJ+wEIfoSghEnexdkJnUHrXf8kDmMTqkI10WxZb6Lx+r6a/kCPMoVg/rDnVectLY8zuCCNhagmm6DR9qygijfOzmMc0LQotL7D6Lf1MUArHm5j0Gjzx58RhPjrqiKeQ7y9M956/IydutOY9OInpZSNMaTJepY8WQDCNcdymmZBvuYujCn0nn5WrxKEDr6PQyLbEEv66HMNhlZ0Ni/3HqiU2uEAt7jJo0Q8dFEjqXK9YntLu9+nyE/Ovwe0hWqzI0ScYPjv+kvuHi3d22wtP0mPn2zVzBcIEudqkadSnj53/fix3yUHQH6pakaEP8xc0X6eqmmoWR92RjHoduKDsxO0txNwE4Wr5XdEeR2y1/m8X2HfMcDTpjG50uy8ezE2Y2aaZIE/5IKHtCwrNcqQ7W5sbM84BLjL7mUSIY2HZa4mCZDDZW0u6q18cNS4kL62sce8I2YbFlkXSEznvpdOyA7S6iggtxPPL3YgkRY5sYfgFXg3QQWggrmgbFzERQzymnr6mEqp2pKcQK26nUxJ7n9jGYiiJD7fp/LC+ZS6EFaxJwnvLB7Eb9VXKgLsMsAerUR3caPcZ2LLdw/Q3PfI1f9uKyWkIPcleeDUp9jHSgm/VwUMAAhey7VVer+JDqZZgMdYyWotUXUQ+Y0alWOr7RDu6zp7HsRsp/aaAwO0qoT+xIvLvzmcRi7u4nMh4DM0SqOxWPz3jkeqAZ/EfWlhSpoqQI4VVWIskLvjO/nZnGCz73e3pLR1ZnEslMLaJT6UPwDxc7KwkgxaHpXLIFjxrDuFSAl9iY6lgvVHt2cIzf7xXoyQDvtuGnOevSStamzEYGLY6Z1dsA0XeINUd9crzh60GLPOmvPtlavx8jCkm"
local function Iljj1jII0jLIOI(lioo01oI)
local lL1Ili1IoOLiO1=(2075172193)+iOljOIO1lOLI
local jo1oi0oL=167
local Il1iiI={}
for jjILll1OL0lO=1,#lioo01oI do
lL1Ili1IoOLiO1=(lL1Ili1IoOLiO1*45197+4018706823)%4294967296
local L0IOILIoIojLoL=llIjOiL01l10(lioo01oI,jjILll1OL0lO)
local IiIl0i=(jo0LOLo1j1IO1(lL1Ili1IoOLiO1/65536)+jo1oi0oL+(jjILll1OL0lO-1)*116)%256
Il1iiI[jjILll1OL0lO]=llIio11l1oL1Il((L0IOILIoIojLoL-IiIl0i)%256)
jo1oi0oL=(jo1oi0oL*37+L0IOILIoIojLoL+1)%251
end
return L1oL1O1LOILjo(Il1iiI)
end
local ilLlL0IL=Iljj1jII0jLIOI(j0Olo0il0Ll1(L0oLlIo1Lo0))
local L0IOILIoIojLoL=1
local function L0ILLjLL0()
local jjILll1OL0lO=llIjOiL01l10(ilLlL0IL,L0IOILIoIojLoL)
L0IOILIoIojLoL=L0IOILIoIojLoL+1
return jjILll1OL0lO
end
local function lojjjli0o0iIl()
local jjILll1OL0lO,ljjLi0L0Lo=llIjOiL01l10(ilLlL0IL,L0IOILIoIojLoL,L0IOILIoIojLoL+1)
L0IOILIoIojLoL=L0IOILIoIojLoL+2
return jjILll1OL0lO+ljjLi0L0Lo*256
end
local function j0OjjIi11ii()
local jjILll1OL0lO,ljjLi0L0Lo,lioo01oI,Il1iiI=llIjOiL01l10(ilLlL0IL,L0IOILIoIojLoL,L0IOILIoIojLoL+3)
L0IOILIoIojLoL=L0IOILIoIojLoL+4
return jjILll1OL0lO+ljjLi0L0Lo*256+lioo01oI*65536+Il1iiI*16777216
end
local function iooLloIIo()
local jjILll1OL0lO=j0OjjIi11ii()
local ljjLi0L0Lo=jOLLjjiLij11(ilLlL0IL,L0IOILIoIojLoL,L0IOILIoIojLoL+jjILll1OL0lO-1)
L0IOILIoIojLoL=L0IOILIoIojLoL+jjILll1OL0lO
return ljjLi0L0Lo
end
local function iiioIO1()
local jjILll1OL0lO=L0ILLjLL0()
local ljjLi0L0Lo=iooLloIIo()
if jjILll1OL0lO==0 then return jlijilI(ljjLi0L0Lo)
elseif jjILll1OL0lO==1 then return ljjLi0L0Lo
elseif jjILll1OL0lO==2 then return 1/0
elseif jjILll1OL0lO==3 then return -1/0
else return 0/0 end
end
local function Lo1oi0IjjojI()
local ll0jLiOjl1oloj=L0ILLjLL0()
local jjILll1OL0lO=L0ILLjLL0()
local ljjLi0L0Lo=lojjjli0o0iIl()
local IOI0o11O={}
for lioo01oI=1,ljjLi0L0Lo do local IoOI1jiijj=lojjjli0o0iIl() IOI0o11O[lioo01oI]={IoOI1jiijj,iooLloIIo()} end
local Il1iiI=j0OjjIi11ii()
local jl1OIoo={}
for lioo01oI=1,Il1iiI do
jl1OIoo[lioo01oI]={lojjjli0o0iIl(),lojjjli0o0iIl(),j0OjjIi11ii(),j0OjjIi11ii()}
end
local L0IOILIoIojLoL=lojjjli0o0iIl()
local LilLIL01IL0i={}
for lioo01oI=1,L0IOILIoIojLoL do LilLIL01IL0i[lioo01oI]=Lo1oi0IjjojI() end
local LIL0iijIlIL1jl=lojjjli0o0iIl()
local Ljjo0j01o0olOI={}
for lioo01oI=1,LIL0iijIlIL1jl do Ljjo0j01o0olOI[lioo01oI]={L0ILLjLL0(),lojjjli0o0iIl()} end
return {ll0jLiOjl1oloj,jjILll1OL0lO,jl1OIoo,IOI0o11O,LilLIL01IL0i,Ljjo0j01o0olOI,{}}
end
local function IO1Ol1lO1Ol(l11oL11jO01I,l11010,IoOI1jiijj)
if l11010[IoOI1jiijj]~=nil then return l11010[IoOI1jiijj] end
local jIoLo0Ooj=l11oL11jO01I[IoOI1jiijj]
local LL11I0L=jIoLo0Ooj[1]
local ijo1ilo1=jIoLo0Ooj[2]
local io0iIlj1O=(14201+LL11I0L*251+1)%65536
local IIiOII0={}
for LL1LO1i0il1O=1,#ijo1ilo1 do
io0iIlj1O=(io0iIlj1O*40503+12345)%65536
IIiOII0[LL1LO1i0il1O]=llIio11l1oL1Il((llIjOiL01l10(ijo1ilo1,LL1LO1i0il1O)-jo0LOLo1j1IO1(io0iIlj1O/256)%256-LL1LO1i0il1O*(14201%256))%256)
end
local iioOIo1II1Lo=L1oL1O1LOILjo(IIiOII0)
local ijioLjLliIi=llIjOiL01l10(iioOIo1II1Lo,1)
local j1olioOLl0I=llIjOiL01l10(iioOIo1II1Lo,2)+llIjOiL01l10(iioOIo1II1Lo,3)*256+llIjOiL01l10(iioOIo1II1Lo,4)*65536+llIjOiL01l10(iioOIo1II1Lo,5)*16777216
local Io11ilIOLIIlLo=jOLLjjiLij11(iioOIo1II1Lo,6,5+j1olioOLl0I)
local LjjOLOiO0II0
if ijioLjLliIi==0 then LjjOLOiO0II0=jlijilI(Io11ilIOLIIlLo) elseif ijioLjLliIi==1 then LjjOLOiO0II0=Io11ilIOLIIlLo elseif ijioLjLliIi==2 then LjjOLOiO0II0=1/0 elseif ijioLjLliIi==3 then LjjOLOiO0II0=-1/0 else LjjOLOiO0II0=0/0 end
l11010[IoOI1jiijj]=LjjOLOiO0II0
return LjjOLOiO0II0
end
local jiilljioLI={}
local i0ljjo=lojjjli0o0iIl()
for jOOjiIo=1,i0ljjo do local jjILll1OL0lO=lojjjli0o0iIl() local ljjLi0L0Lo=lojjjli0o0iIl() jiilljioLI[jjILll1OL0lO]=ljjLi0L0Lo end
local iolLI01l=Lo1oi0IjjojI()
local iI0Ijo11liI
local function i1ooIjjj(iolLI01l,Ljjo0j01o0olOI)
return function(...) return iI0Ijo11liI(iolLI01l,Ljjo0j01o0olOI,iji1ijiOl(...)) end
end
iI0Ijo11liI=function(iolLI01l,Ljjo0j01o0olOI,lIlOo0O1Ollli)
local ij0lI0={}
local jllIlIjLIOllj1=0
local ll0jLiOjl1oloj=iolLI01l[1]
local IOIOjIOOoOLjL=lIlOo0O1Ollli.n
for jjILll1OL0lO=1,ll0jLiOjl1oloj do ij0lI0[jjILll1OL0lO-1]=lIlOo0O1Ollli[jjILll1OL0lO] end
local i0IlO1IL,iIlLOI={},0
if iolLI01l[2]==1 then iIlLOI=IOIOjIOOoOLjL-ll0jLiOjl1oloj; if iIlLOI<0 then iIlLOI=0 end; for jjILll1OL0lO=1,iIlLOI do i0IlO1IL[jjILll1OL0lO]=lIlOo0O1Ollli[ll0jLiOjl1oloj+jjILll1OL0lO] end end
local jl1OIoo,IOI0o11O,LilLIL01IL0i=iolLI01l[3],iolLI01l[4],iolLI01l[5]
local Lj0i1iOoO0Ioji=iolLI01l[7]
local i1lLiiILL0Ooio=1
local LIL0iijIlIL1jl=0
while true do
local I00LlIOOLlOI=jl1OIoo[i1lLiiILL0Ooio]
i1lLiiILL0Ooio=i1lLiiILL0Ooio+1
local IlijOIi110I0l0,jjILll1OL0lO,ljjLi0L0Lo,lioo01oI=I00LlIOOLlOI[1],I00LlIOOLlOI[2],I00LlIOOLlOI[3],I00LlIOOLlOI[4]
local Il1iiI=jiilljioLI[IlijOIi110I0l0]
if (i1lLiiILL0Ooio*(i1lLiiILL0Ooio+1)*(i1lLiiILL0Ooio+2))%3~=0 then jllIlIjLIOllj1=jllIlIjLIOllj1-2 end
if Il1iiI==5 then
ij0lI0[jjILll1OL0lO]=IO1Ol1lO1Ol(IOI0o11O,Lj0i1iOoO0Ioji,ljjLi0L0Lo+1)
elseif Il1iiI==26 then
ij0lI0[jjILll1OL0lO]={ij0lI0[ljjLi0L0Lo]}
elseif Il1iiI==14 then
if (not not ij0lI0[jjILll1OL0lO])==(ljjLi0L0Lo~=0) then i1lLiiILL0Ooio=lioo01oI+1 end
elseif Il1iiI==38 then
ij0lI0[jjILll1OL0lO]=Ljjo0j01o0olOI[ljjLi0L0Lo+1][1]
elseif Il1iiI==37 then
Ljjo0j01o0olOI[ljjLi0L0Lo+1][1]=ij0lI0[jjILll1OL0lO]
elseif Il1iiI==43 then
i1lLiiILL0Ooio=ljjLi0L0Lo+1
elseif Il1iiI==18 then
local ijo1ilo1
if ljjLi0L0Lo==0 then ijo1ilo1=LIL0iijIlIL1jl-jjILll1OL0lO else ijo1ilo1=ljjLi0L0Lo-1 end
local io0iIlj1O={}
for jIoLo0Ooj=1,ijo1ilo1 do io0iIlj1O[jIoLo0Ooj]=ij0lI0[jjILll1OL0lO+jIoLo0Ooj-1] end
return joii1Ij(io0iIlj1O,1,ijo1ilo1)
elseif Il1iiI==24 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo][ij0lI0[lioo01oI]]
elseif Il1iiI==21 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]<=ij0lI0[lioo01oI])
elseif Il1iiI==7 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]-ij0lI0[ljjLi0L0Lo]%ij0lI0[lioo01oI])/ij0lI0[lioo01oI]
elseif Il1iiI==1 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]*ij0lI0[lioo01oI]
elseif Il1iiI==40 then
ij0lI0[ljjLi0L0Lo][1]=ij0lI0[jjILll1OL0lO]
elseif Il1iiI==3 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]+ij0lI0[lioo01oI]
elseif Il1iiI==4 then
IilI0O[IO1Ol1lO1Ol(IOI0o11O,Lj0i1iOoO0Ioji,ljjLi0L0Lo+1)]=ij0lI0[jjILll1OL0lO]
elseif Il1iiI==29 then
ij0lI0[jjILll1OL0lO]=ij0lI0[jjILll1OL0lO]+ij0lI0[jjILll1OL0lO+2]
local LL11I0L=ij0lI0[jjILll1OL0lO+2]
if (LL11I0L>0 and ij0lI0[jjILll1OL0lO]<=ij0lI0[jjILll1OL0lO+1]) or (LL11I0L<=0 and ij0lI0[jjILll1OL0lO]>=ij0lI0[jjILll1OL0lO+1]) then ij0lI0[jjILll1OL0lO+3]=ij0lI0[jjILll1OL0lO]; i1lLiiILL0Ooio=ljjLi0L0Lo+1 end
elseif Il1iiI==30 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]/ij0lI0[lioo01oI]
elseif Il1iiI==12 then
local ijo1ilo1
if ljjLi0L0Lo==0 then ijo1ilo1=LIL0iijIlIL1jl-jjILll1OL0lO-1 else ijo1ilo1=ljjLi0L0Lo end
local LL11I0L=ij0lI0[jjILll1OL0lO]
for jIoLo0Ooj=1,ijo1ilo1 do LL11I0L[lioo01oI+jIoLo0Ooj]=ij0lI0[jjILll1OL0lO+jIoLo0Ooj] end
elseif Il1iiI==27 then
ij0lI0[jjILll1OL0lO]=not ij0lI0[ljjLi0L0Lo]
elseif Il1iiI==33 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]..ij0lI0[lioo01oI]
elseif Il1iiI==32 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]<ij0lI0[lioo01oI])
elseif Il1iiI==16 then
local LL11I0L=LilLIL01IL0i[ljjLi0L0Lo+1]
local io0iIlj1O={}
local IIiOII0=LL11I0L[6]
for jIoLo0Ooj=1,#IIiOII0 do
local LL1LO1i0il1O=IIiOII0[jIoLo0Ooj]
if LL1LO1i0il1O[1]==1 then io0iIlj1O[jIoLo0Ooj]=ij0lI0[LL1LO1i0il1O[2]] else io0iIlj1O[jIoLo0Ooj]=Ljjo0j01o0olOI[LL1LO1i0il1O[2]+1] end
end
ij0lI0[jjILll1OL0lO]=i1ooIjjj(LL11I0L,io0iIlj1O)
elseif Il1iiI==17 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]-ij0lI0[lioo01oI]
elseif Il1iiI==31 then
local LL11I0L=ij0lI0[jjILll1OL0lO]
local iioOIo1II1Lo=ij0lI0[jjILll1OL0lO+1]
local ijioLjLliIi=ij0lI0[jjILll1OL0lO+2]
local IIiOII0=iji1ijiOl(LL11I0L(iioOIo1II1Lo,ijioLjLliIi))
local LL1LO1i0il1O=IIiOII0[1]
if LL1LO1i0il1O~=nil then
ij0lI0[jjILll1OL0lO+2]=LL1LO1i0il1O
for jIoLo0Ooj=1,ljjLi0L0Lo do ij0lI0[jjILll1OL0lO+3+jIoLo0Ooj-1]=IIiOII0[jIoLo0Ooj] end
i1lLiiILL0Ooio=lioo01oI+1
end
elseif Il1iiI==19 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]%ij0lI0[lioo01oI]
elseif Il1iiI==13 then
ij0lI0[jjILll1OL0lO]=(ljjLi0L0Lo~=0)
elseif Il1iiI==23 then
if ljjLi0L0Lo==0 then
for jIoLo0Ooj=1,iIlLOI do ij0lI0[jjILll1OL0lO+jIoLo0Ooj-1]=i0IlO1IL[jIoLo0Ooj] end
LIL0iijIlIL1jl=jjILll1OL0lO+iIlLOI
else
for jIoLo0Ooj=1,ljjLi0L0Lo-1 do ij0lI0[jjILll1OL0lO+jIoLo0Ooj-1]=i0IlO1IL[jIoLo0Ooj] end
end
elseif Il1iiI==8 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]>ij0lI0[lioo01oI])
elseif Il1iiI==11 then
ij0lI0[jjILll1OL0lO][ij0lI0[ljjLi0L0Lo]]=ij0lI0[lioo01oI]
elseif Il1iiI==42 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]^ij0lI0[lioo01oI]
elseif Il1iiI==20 then
local LL11I0L=ij0lI0[jjILll1OL0lO]
local ijo1ilo1
if ljjLi0L0Lo==0 then ijo1ilo1=LIL0iijIlIL1jl-jjILll1OL0lO-1 else ijo1ilo1=ljjLi0L0Lo-1 end
local io0iIlj1O={}
for jIoLo0Ooj=1,ijo1ilo1 do io0iIlj1O[jIoLo0Ooj]=ij0lI0[jjILll1OL0lO+jIoLo0Ooj] end
local IIiOII0=iji1ijiOl(LL11I0L(joii1Ij(io0iIlj1O,1,ijo1ilo1)))
if lioo01oI==0 then
local LL1LO1i0il1O=IIiOII0.n
for jIoLo0Ooj=1,LL1LO1i0il1O do ij0lI0[jjILll1OL0lO+jIoLo0Ooj-1]=IIiOII0[jIoLo0Ooj] end
LIL0iijIlIL1jl=jjILll1OL0lO+LL1LO1i0il1O
else
for jIoLo0Ooj=1,lioo01oI-1 do ij0lI0[jjILll1OL0lO+jIoLo0Ooj-1]=IIiOII0[jIoLo0Ooj] end
end
elseif Il1iiI==41 then
ij0lI0[jjILll1OL0lO]=((ij0lI0[jjILll1OL0lO] or 0)+ljjLi0L0Lo)%(lioo01oI+1)
elseif Il1iiI==2 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo][1]
elseif Il1iiI==39 then
ij0lI0[jjILll1OL0lO]=-ij0lI0[ljjLi0L0Lo]
elseif Il1iiI==9 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]==ij0lI0[lioo01oI])
elseif Il1iiI==25 then
ij0lI0[jjILll1OL0lO]=ij0lI0[jjILll1OL0lO]-ij0lI0[jjILll1OL0lO+2]; i1lLiiILL0Ooio=ljjLi0L0Lo+1
elseif Il1iiI==36 then
ij0lI0[jjILll1OL0lO+1]=ij0lI0[ljjLi0L0Lo]; ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo][ij0lI0[lioo01oI]]
elseif Il1iiI==6 then
ij0lI0[jjILll1OL0lO]=#ij0lI0[ljjLi0L0Lo]
elseif Il1iiI==28 then
for jIoLo0Ooj=jjILll1OL0lO,jjILll1OL0lO+ljjLi0L0Lo do ij0lI0[jIoLo0Ooj]=nil end
elseif Il1iiI==34 then
ij0lI0[jjILll1OL0lO]=ij0lI0[ljjLi0L0Lo]
elseif Il1iiI==10 then
ij0lI0[jjILll1OL0lO]={}
elseif Il1iiI==15 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]~=ij0lI0[lioo01oI])
elseif Il1iiI==35 then
ij0lI0[jjILll1OL0lO]=(ij0lI0[ljjLi0L0Lo]>=ij0lI0[lioo01oI])
elseif Il1iiI==22 then
ij0lI0[jjILll1OL0lO]=IilI0O[IO1Ol1lO1Ol(IOI0o11O,Lj0i1iOoO0Ioji,ljjLi0L0Lo+1)]
else Io1LijiIj0LOI() end
end
return jllIlIjLIOllj1
end
return iI0Ijo11liI(iolLI01l,{},iji1ijiOl(...))
