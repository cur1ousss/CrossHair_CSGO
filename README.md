# CrossHair (Unformmated :( )

# str() vs repr()

from types import CodeType


a=[1,2,3,4]
b='sample string'

print(str(a))
print(repr(a))

print(str(b))
print(repr(b))

# str a     [1, 2, 3, 4] 
# repr a    [1, 2, 3, 4] 
# str b     sample string
# repr b    'sample string'


# str() returns a string containing nicely printable represenation of an object, for strings returns the string itself 
    # repr() vs str() -> str() does'nt always attempt to return a string that is acceptable to eval() , its goal is to return a printable string if no argument is given it returns a empty string
    # repr() returns a string containing printable representation of an object , is the same value yielded by conversions{reverse quotes} 1:59 more text >> https://www.youtube.com/watch?v=5cvM-crlDvg

# goal of repr() is to be unambiguous
# goal of str() is to be readable


# example
    # >> can run output of repr() as py code 

import datetime
import pytz

a=datetime.datetime.utcnow().replace(tzinfo=pytz.UTC)
b=str(a)

print(f'str(a) {str(a)}')
print(f'str(b) {str(b)}')

print(f'\nrepr(a) {repr(a)}')
print(f'repr(b) {repr(b)}')


# str(a) 2021-11-23 17:09:23.271332+00:00
# str(b) 2021-11-23 17:09:23.271332+00:00

# repr(a) datetime.datetime(2021, 11, 23, 17, 9, 23, 271332, tzinfo=<UTC>)
# repr(b) '2021-11-23 17:09:23.271332+00:00'    
        # repr() helps to find doodh ka doodh paani ka paani makes them unambiguos finds amogos

# repr() meant for debugging
    # example if value returned from database help convert that check 
            # since str() value will be same , repr() will help find amogus
 
 
 
 EXILE
 
 # useful for small medium applications database and prototyping 
# part of standard library

# database can be a simple file
    # or a in memory database that lives in ram

# employee.py >>
class Employee:
    """A sample Employee class"""

    def __init__(self,first,last,pay):
        self.first=first
        self.last=last
        self.pay=pay

    @property
    def email(self):
        return f'{self.first}.{self.last}@email.com'

    @property
    def fullname(self):
        return f'{self.first} {self.last}'

    def __repr__(self):
        return "Employee('{}','{}',{})".format(self.first,self.last,self.pay)



# sqliteDemo.py >>
import sqlite3

con=sqlite3.connect(':memory:')
    # in connect() can pass file where we want to store our data or we can make in memory database :memory:
con=sqlite3.connect('employee.db')
        # if not exists creates .db in same directory
        # if exists then just connects not overwrite

# cursor helps execute sql commands 
    # cursor c below
c=con.cursor()

# run sql commands using execute() method
    # use docstring to pass command since syntax maintained no unexpected newlines
    # for single line commands can use simple "" quotes like string no need docstring
c.execute("""CREATE TABLE employees(
    first text,
    last text,
    pay integer
    )""")
    # columnName DataType
    # limited datatypes in sqlite 
        # https://www.sqlite.org/datatype3.html

c.execute("INSERT INTO employees VALUES ('Corey','Schafer',50000)")

c.execute("SELECT * FROM employees WHERE LAST='Schafer'")

# to iterate through returned result
c.fetchone() 
    # will get the next row in our results and only return that row , if no more rows available returns None
c.fetchmany(5)
    # returns that number of rows as a list
    # if no more rows available returns an empty list

c.fetchall()
    # returns rows as list
    # if no more rows left returns an empty list


print(c.fetchone())
property(c.fetchall())

c.execute("INSERT INTO employees VALUES ('Corey','Schafer',50000)")
c.execute("SELECT * FROM employees WHERE LAST='Schafer'")
    # when run select() statement below insert automatically auto commits our insert transaction above
        # can also explicitly con.commit() between insert and select

con.commit() # not cursor c.commit() 
    # commits the current transaction

con.close()
    # close connection to database / close resources











#########################################################################################################################################
CrossHair Hash
https://github.com/mija/yuki.cfg

https://support.lenovo.com/us/en/videos/vid500028

Old White xantares santaares >> CSGO-23R4C-ziJeC-rV85K-YHGXj-ztZpG

Current Blue Short zero gap >> CSGO-MQrmz-Q4AuO-2aM9U-OxMzC-YZRVP

Banana Circle green blue >> CSGO-jxxQP-BSftd-n9ov3-LSePq-PXOYE

Banana Circle >> CSGO-mPpkR-d2htN-RQCfd-yJneX-HRz6A 

 current Green Circle Gap >> CSGO-szKMK-stSX9-BfMEN-zymAD-M4syM

Circle Green Gap >> CSGO-cSCq8-XiPXt-5WkEu-S9Y4i-BNzMM

Furiosss >> CSGO-RDuOv-JZRvh-HypGW-3YBQq-d7qRP

Current Green Gap >> CSGO-cSCq8-XiPXt-5WkEu-S9Y4i-BNzMM

Strange ancient Crosshair >> CSGO-eYWKx-tzKFD-jEAYt-AN3tq-uL88F

https://app.scope.gg/matches/3473896033644183879


Description Crosshair >>  #CROSSHAIR
Green Gap Circle CURRENT >> CSGO-szKMK-stSX9-BfMEN-zymAD-M4syM
GREEN GAP  >> CSGO-cSCq8-XiPXt-5WkEu-S9Y4i-BNzMM
White_Scope_Crosshair>> CSGO-23R4C-ziJeC-rV85K-YHGXj-ztZpG
Green short fat gap >>CSGO-M6hQa-p6Wya-qrnuo-anLMh-ia4NF 
CSGO-ETE4q-4jVRJ-fbMC5-JNT48-T3SKF
CSGO-eYWKx-tzKFD-jEAYt-AN3tq-uL88F
Random?? >>CSGO-2u3cF-yNiue-nDjPk-tsu7j-OEH8D

https://steamcommunity.com/id/suziop/
igl cynic
bakchod profile gifs- http://steamcommunity.com/profiles/76561198410762618
https://steamcommunity.com/profiles/76561198355329253 Vaibhav Singh Khutney Korba BakchodLaunda sg wala lalten osama bin

https://steamcommunity.com/profiles/76561198171300782 Fast af Cactus Timeis But a window Friend youtuber

https://steamcommunity.com/profiles/76561198838534727 >> Deadpool good guy

furii profile >> http://steamcommunity.com/profiles/76561198146838248
Youtuber Vacced>> https://steamcommunity.com/profiles/76561198977386758
Vacced Profile Grimjow>> http://steamcommunity.com/profiles/76561198870421945
TradeBanned >> https://steamcommunity.com/profiles/76561198983754496

fucking bot Buy order low snipe https://steamcommunity.com/profiles/76561198341989198/inventory/

art http://steamcommunity.com/profiles/76561198167110743

Anime Tiddie lmao https://steamcommunity.com/profiles/76561198387793458

Achievements - Literally nothing, I'm the definition of mediocrity and wasting my time on a video game that i will never amount to anything on. Only reason i still play this game is because i need to fill the gawddamn void in my life that living in this ♥♥♥♥♥♥ country amongst ♥♥♥♥♥♥ people has created in me. I should quit, honestly. And if you are reading this bio, so should you.https://steamcommunity.com/profiles/76561198339206424/

awp hydra #1 sheeter https://steamcommunity.com/profiles/76561199211336774 http://steamcommunity.com/profiles/76561198040974567

anti scam https://steamcommunity.com/sharedfiles/filedetails/?id=784477482&tscn=1622905649

http://steamcommunity.com/profiles/76561198984752198 multi art

sastiraaaand http://steamcommunity.com/profiles/76561198412322254
arriBra http://steamcommunity.com/profiles/76561198969510646

http://steamcommunity.com/profiles/76561199049845311

catfish maybe http://steamcommunity.com/profiles/76561198849719436

http://steamcommunity.com/profiles/76561198122773989 scammer comment on screenshot mine

https://help.steampowered.com/en/faqs/view/46DB-4CEC-F7E9-49E5 >> OW bans on players
https://steamcommunity.com/profiles/76561198145654617 shemale
https://steamcommunity.com/profiles/76561198308724504 laundiya friend of above
http://steamcommunity.com/profiles/76561198930822005 bakchod description 
(╭☞•́⍛•̀)╭☞ बाप से हिसाब से। जनहित में जारी। (◠‿◕)

:ButterflyBeydo: ily.. :ButterflyBeydo:

"Her memories are
like alcohol,
can't deny it.
The more I drink,
the more it feels good.

But the moment I realize
its too much,
its already too late...💔"
- A 15 yr old kid

𝕶𝖓𝖔𝖜𝖎𝖓𝖌 𝖞𝖔𝖚𝖗 𝖔𝖜𝖓 𝖉𝖆𝖗𝖐𝖓𝖊𝖘𝖘 𝖎𝖘 𝖙𝖍𝖊 𝖇𝖊𝖘𝖙 𝖒𝖊𝖙𝖍𝖔𝖉 𝖋𝖔𝖗 𝖉𝖊𝖆𝖑𝖎𝖓𝖌 𝖜𝖎𝖙𝖍 𝖙𝖍𝖊 𝖉𝖆𝖗𝖐𝖓𝖊𝖘𝖘𝖊𝖘 𝖔𝖋 𝖔𝖙𝖍𝖊𝖗 𝖕𝖊𝖔𝖕𝖑𝖊.
- 𝕾𝖆𝖒𝖚𝖊𝖑 𝕷. 𝕵𝖆𝖈𝖐𝖘𝖔𝖓

SARA + toxic + racist player dudeh...*smh, fix ur attidude bro, dont waste ur time for potato gaming, but focus increase your points at school, for make ur parents happy, dont be like burden..ok, good game and have a nice day:espresso::steamthumbsup: http://steamcommunity.com/profiles/76561199017849512 comments reketed

https://steamcommunity.com/profiles/76561198142717073/  nepal game mart

https://steamcommunity.com/id/dgmdevgaming/inventory/

https://steamcommunity.com/id/grbiceps/ pROOO

http://steamcommunity.com/profiles/76561198450340284 dope gold diamond talon

cluck deag 3x 1x scarred http://steamcommunity.com/profiles/76561198153678139

hive guide https://steamcommunity.com/sharedfiles/filedetails/?id=878908361
ch guide https://broskins.com/index.php?threads/case-hardened-gold-gem-guide-patterns.276/
lmao mp7 sheeter https://www.youtube.com/watch?v=Ef7eb9sPQBs https://steamcommunity.com/profiles/76561198121054003

Teri Keh K Lunga.. Teri mummy ko raat bhar dunga - http://steamcommunity.com/profiles/76561198314461861

Hey future pros, here another pro tip for you all out there. Hide chat for an instant increase in iq and a better viewing experience. See you on the server!

bakchod lawdi http://steamcommunity.com/profiles/76561199000710477
Furiousss
CSGO-RDuOv-JZRvh-HypGW-3YBQq-d7qRP

green dot 
CSGO-GvmzX-sdUDN-PeU2h-Hqkbq-yUapG

blue gap
CSGO-OmR7v-p4PAv-qHNaa-Dpij9-onYbD

white fat luna cross crosshair
CSGO-k8ArB-PcRs7-6nam5-vMKYj-jruCQ

green short
CSGO-hvx2E-ksqhs-coA74-eE4MO-iKZfE

blue long
CSGO-dK2Uo-uzpVs-nH4e4-mv76Z-ZxAkE

blue short
CSGO-3fFeo-DrJjY-OwHJ7-OEThH-CFCEB

blue short fat
CSGO-AhyV7-UcduS-OjqTL-krdBc-VqnkP


white cross
CSGO-66z84-uxv84-WaFtp-6SVmp-cAPEL

red dynamic
CSGO-QHbor-VfxML-rO3T6-hWzJq-7FwzF

               ⢀⣠⠤⠤⣀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⣚⣥⣤⠀⠀⢀⡷⠔⠒⠒⠲⠦⡀
⠀⠀⠀⠀⠀⠀⠀⠀⢀⢎⣾⣿⠟⠁⡠⠖⣡⣶⣶⣶⠀⠀⠀⡇
⠀⠀⠀⠀⠀⠀⠀⡔⣱⣿⠟⠁⡠⠊⣠⣾⣿⡿⠟⠁⠀⢀⠌
⠀⠀⠀⠀⢀⠔⠉⠀⠀⠀⠀⠉⠀⠘⠛⠛⠁⠀⣀⠤⠚⠁
⠀⠀⠀⡔⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⢯⠁
⠀⠀⡸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢱ 𝓐𝓒𝓒𝓔𝓟𝓣 𝓜𝓨
⠀⣰⠁⠀⣤⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹ 𝓕𝓡𝓘𝓔𝓝𝓓 𝓡𝓔𝓠𝓤𝓔𝓢𝓣
⢰⠃⠀⠀⠛⠁⠐⠂⠀⣿⡗⠀⠀⠀⠀⠀⠀⠀⢹
⠈⢧⣠⣾⣷⣦⣠⣶⣿⣿⣦⠀⠀⠀⠀⠀⠀⠀⡇
⠒⠒⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⡰
⠀⠀⠈⢿⣿⣿⣿⣿⣯⡉⠉⠉⠒⠲⢤⡔⠁
⢀⠔⠁⠈⠻⣿⣿⡿⡋⠉⠓⠦⡄⠀⠀⠉⢫⠉⡆
⠀⠀⠀⠀⠀⡐⠀⠀⠀⠈⢢⠤⠤⠜⠀⠀⠀⠀⡗⠁
⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⢇⡀⡖⠒⠒⠤⣀


⣿⠟⣫⢸⣿⢿⣿⣾⣿⢿⣿⣿⢻⣿⣿⣿⢿⣿⣿⣿⢸⣿⣼⣿⣿⣿⣿⣿⣿⣿
⡟⢸⣟⢸⣿⠸⣷⣝⢻⠘⣿⣿⢸⢿⣿⣿⠄⣿⣿⣿⡆⢿⣿⣼⣿⣿⣿⣿⢹⣿
⡇⣿⡿⣿⣿⢟⠛⠛⠿⡢⢻⣿⣾⣞⣿⡏⠖⢸⣿⢣⣷⡸⣇⣿⣿⣿⢼⡿⣿⣿
⣡⢿⡷⣿⣿⣾⣿⣷⣶⣮⣄⣿⣏⣸⣻⣃⠭⠄⠛⠙⠛⠳⠋⣿⣿⣇⠙⣿⢸⣿
⠫⣿⣧⣿⣿⣿⣿⣿⣿⣿⣿⣿⠻⣿⣾⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣹⢷⣿⡼⠋
⠄⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⣿⣿⠄⠄
⠄⠄⢻⢹⣿⠸⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣼⣿⣿⣿⣿⡟⠄⠄
⠄⠄⠈⢸⣿⠄⠙⢿⣿⣿⣹⣿⣿⣿⣿⣟⡃⣽⣿⣿⡟⠁⣿⣿⢻⣿⣿⢿⠄⠄
⠄⠄⠄⠘⣿⡄⠄⠄⠙⢿⣿⣿⣾⣿⣷⣿⣿⣿⠟⠁⠄⠄⣿⣿⣾⣿⡟⣿⠄⠄
⠄⠄⠄⠄⢻⡇⠸...𝐻𝒶𝓋𝑒 𝒶 𝐿𝑜𝓋𝑒𝓁𝓎 𝒹𝒶𝓎.....⣿⣇⣿⣿⢿⣿⠄⠄

𝕿𝖍𝖊 S𝖈𝖆𝖗𝖘 𝖙𝖍𝖆𝖙 y𝖔𝖚 𝖈𝖆𝖓'𝖙 𝖘𝖊𝖊 𝖆𝖗𝖊 𝖙𝖍𝖊 𝖍𝖆𝖗𝖉𝖊𝖘𝖙 𝖙𝖔 𝖍𝖊𝖆𝖑.


⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⣀⠄⠄⠸⢒⢶⣷⣶⣶⣶⣶⣶⢖⠤⠄⠂⠄⢰⠄⠄
⠄⠄⢠⣥⣠⣄⠄⢀⣙⢿⣿⣿⣿⣿⡿⣁⠠⠄⣰⣆⣤⣆⡀
⠄⣠⣷⣫⢳⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣺⣇
⢰⣿⢣⣿⢹⣿⣿⣿⣿⣿⣿⡻⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⢿⣿⣿⣿⣸⣿⣿⣿⣿⣿⣿⣻⣝⣿⣿⣿⣿⣿⣿⣇⣿⡇⣿
⠸⣿⣷⣿⣯⣻⣿⣿⣿⣿⣿⡿⡿⣿⣿⣿⣿⡿⣿⣾⣟⣽⡟
⠄⠨⢹⣷⣿⣿⣷⣯⣿⢿⣖⡶⢲⣼⣿⢟⣽⣾⣿⠿⠊⠁⠄
⠄⠄⠄⢭⣭⣵⣿⣿⣿⣯⣿⣿⣿⣿⣳⣿⣿⣿⣷⣶⠟⠁⠄
⠄⠄⠄⠄⠘⠻⣿⣿⣿⣿⣷⠛⠉⣵⣿⣿⣿⣿⠟⠃⠄⠄⠄
⠄⠄⠄⠄⠄⠄⢹⣿⣿⣿⣿⠄⠄⣿⣿⣿⣿⡃⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⢀⣾⣿⣿⣿⠃⠄⠄⢸⣿⣿⣿⣇⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⣼⣿⣿⣿⡏⠄⠄⠄⠘⣿⣿⣿⣿⡄⠄⠄⠄⠄
⠄⠄⠄⠄⢸⣿⣿⣿⣿⡇⠄⠄⠄⠄⣿⣿⣿⣿⣧⠄⠄⠄⠄

█▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀▀█
█░░╦─╦╔╗╦─╔╗╔╗╔╦╗╔╗░░█
█░░║║║╠─║─║─║║║║║╠─░░█
█░░╚╩╝╚╝╚╝╚╝╚╝╩─╩╚╝░░█
█▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄█

──▄────▄▄▄▄▄▄▄────▄───
─▀▀▄─▄█████████▄─▄▀▀──
─────██─▀███▀─██──────
───▄─▀████▀████▀─▄────
─▀█────██▀█▀██────█▀──
𝒲𝐸𝐿𝒞𝒪𝑀𝐸 ツ 𝓵𝓮𝓪𝓿𝓮 𝔂𝓸𝓾𝓻 𝓹𝓻𝓮𝓼𝓮𝓷𝓬𝓮 𝓽𝓱𝓻𝓸𝓾𝓰𝓱 𝓬𝓸𝓶𝓶𝓮𝓷𝓽.
░░░░░░▄▄▄░░▄██▄
░░░░░▐▀█▀▌░░░░▀█▄
░░░░░▐█▄█▌░░░░░░▀█▄
░░░░░░▀▄▀░░░▄▄▄▄▄▀▀
░░░░▄▄▄██▀▀▀▀
░░░█▀▄▄▄█░▀▀
░░░▌░▄▄▄▐▌▀▀▀
▄░▐░░░▄▄░█░▀▀
▀█▌░░░▄░▀█▀░▀
░░░░░░░▄▄▐▌▄▄
░░░░░░░▀███▀█░▄
░░░░░░▐▌▀▄▀▄▀▐▄
░░░░░░▐▀░░░░░░▐▌
░░░░░░█░░░░░░░░█
░░░░░▐▌░░░░░░░░░█
░░░░░█░░░░░░░░░░▐▌

⢸AK Paai ?
⢸
⢸⡀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣶⣿⣶⣄
⢿⣿⣄⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣄
⠀⠹⣿⣧⣀⣠⣴⣾⣷⣿⣷⠾⢷⠋⠀⠀⠀⠀⠀⠀⠀⣼⣿⣿⣿⡷
⠀⠀⠈⢿⡿⠟⢻⣿⣿⣿⣿⣿⣿⣷⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⣿⡟
⠀⠀⠀⠀⠀⠀⣼⣿⣿⣿⣿⣿⡟⢿⣿⣄⠀⠀⠀⠀⢠⣶⣾⣿⡇
⠀⠀⠀⠀⠀⠀⣿⣿⣿⣿⣿⣿⡇⠀⠙⠿⡿⢆⣴⣿⣿⣿⣿⡇
⠀⠀⠀⠀⠀⢰⣿⣿⣿⣿⣿⣿⠀⠀⣤⣶⣾⣿⣿⣿⣿⣷⠹⣷⣤⣤⣄⣀⡀
⠀⠀⠀⠀⠀⢸⣿⣿⡏⣿⣿⣿⢀⣾⣿⣿⣿⣿⣏⠀⠀⢀⣀⣈⣉⣉⣉⣙⣁⣀
⠀⠀⠀⠀⠀⢸⣿⣿⡇⣿⣿⢏⣾⣿⣿⣿⣿⣿⣿⣆
⠀⠀⠀⠀⠀⢸⣿⣿⡇⣿⣿⣷⠈⠉⠙⠛⢻⣭⣷
⠀⠀⠀⠀⠀⢸⣿⣿⡇⣿⣿⣿⠀⠀⠀⠀⠀⢹⣿⣷
⠀⠀⠀⠀⠀⢸⣿⣿⡇⣿⣿⣿⠀⠀⠀⠀⠀⣾⣿⡏
⠀⠀⠀⠀⠀⢸⣿⣿⡇⣿⣿⣿⠀⠀⠀⠀⢰⣿⣿
⠀⠀⠀⠀⠀⠘⢿⡿⠇⠻⣿⠟⠀⠀⠀⠀⢿⣿⠇

"⣿⣿⣿⡇⢩⠘⣴⣿⣥⣤⢦⢁⠄⠉⡄⡇⠛⠛⠛⢛⣭⣾⣿⣿⡏
⣿⣿⣿⡇⠹⢇⡹⣿⣿⣛⣓⣿⡿⠞⠑⣱⠄⢀⣴⣿⣿⣿⣿⡟
⣿⣿⣿⣧⣸⡄⣿⣪⡻⣿⠿⠋⠄⠄⣀⣀⢡⣿⣿⣿⣿⡿⠋
⠘⣿⣿⣿⣿⣷⣭⣓⡽⡆⡄⢀⣤⣾⣿⣿⣿⣿⣿⡿⠋
⠄⢨⡻⡇⣿⢿⣿⣿⣭⡶⣿⣿⣿⣜⢿⡇⡿⠟⠉
⠄⠸⣷⡅⣫⣾⣿⣿⣿⣷⣙⢿⣿⣿⣷⣦⣚⡀
⠄⠄⢉⣾⡟⠙❤️⠈⢻⣿⣷⣅⢻⣿⣿⣿⣿⣿⣶⣶⡆⠄⡀
⠄⢠⣿⣿⣧⣀⣀⣀⣀⣼⣿⣿⣿⡎⢿⣿⣿⣿⣿⣿⣿⣇❤️⠄
⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢇⣎⢿⣿⣿⣿⣿⣿⣿⣿⣶⣶
⠄⠄⠻⢿⣿⣿⣿⣿⣿⣿⣿⢟⣫⣾⣿⣷⡹⣿⣿⣿⣿⣿⣿⣿⡟
⠄⠄⠄⠄⢮⣭⣍⡭⣭⡵⣾⣿⣿⣿⡎⣿⣿⣌⠻⠿⠿⠿⠟⠋
⠄⠄⠄⠄⠈⠻⣿⣿⣿⣿⣹⣿⣿⣿⡇⣿⣿⡿
⠄⠄⣀⣴⣾⣶⡞⣿⣿⣿⣿⣿⣿⣿⣾⣿⡿⠃
⣠⣾⣿⣿⣿⣿⣿⣹⣿⣿⣿⣿⣿⡟⣹⣿⣳⡄"
⠄⣿⣷⣯⣭⡷⠄⠄⢀⣀⠩⠍⢉⣛⣛⠫⢏⣈⣭⣥⣶⣶⣦⣭⣛⠄⠄⠄⠄⠄
⢀⣿⣿⣿⡿⠃⢀⣴⣿⣿⣿⣎⢩⠌⣡⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠄⠄⠄
⢸⡿⢟⣽⠎⣰⣿⣿⣿⣿⣿⣿⢀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⠄⠄
⣰⠯⣾⢅⣼⣿⣿⣿⣿⣿⣿⡇⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⠄
⢰⣄⡉⣼⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⠄
⢯⣌⢹⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⢸⣇⣽⣿⣿⣿⣿⣿⣿⣿⣿⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⢸⣟⣧⡻⣿⣿⣿⣿⣿⣿⣿⣧⡻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠈⢹⡧⣿⣸⠿⢿⣿⣿⣿⣿⡿⠗⣈⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄
⠄⠘⢷⡳⣾⣷⣶⣶⣶⣶⣶⣾⣿⣿⢀⣶⣶⣶⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⠇⠄

_____Sexy?Sex
____?Sexy?Sexy
___y?Sexy?Sexy?
___?Sexy?Sexy?S
___?Sexy?Sexy?S
__?Sexy?Sexy?Se
_?Sexy?Sexy?Se
_?Sexy?Sexy?Se
_?Sexy?Sexy?Sexy?
?Sexy?Sexy?Sexy?Sexy
?Sexy?Sexy?Sexy?Sexy?Se
?Sexy?Sexy?Sexy?Sexy?Sex
_?Sexy?__?Sexy?Sexy?Sex
___?Sex____?Sexy?Sexy?
___?Sex_____?Sexy?Sexy
___?Sex_____?Sexy?Sexy
____?Sex____?Sexy?Sexy
_____?Se____?Sexy?Sex
______?Se__?Sexy?Sexy
_______?Sexy?Sexy?Sex
________?Sexy?Sexy?sex
_______?Sexy?Sexy?Sexy?Se
_______?Sexy?Sexy?Sexy?Sexy?
_______?Sexy?Sexy?Sexy?Sexy?Sexy
_______?Sexy?Sexy?Sexy?Sexy?Sexy?
________?Sexy?Sexy____?Sexy?Sexy?
_________?Sexy?Se_______?SexySexy?
_________?Sexy?Se_____?Sexy?Sexy?
_________?Sexy?S____?Sexy?Sexy
_________?Sexy?S_?Sexy?Sexy
________?Sexy?Sexy?Sexy
________?Sexy?Sexy?S
________?Sexy?Sexy
_______?Sexy?Se
_______?Sexy?
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠛⢻⣿⣯⣿⣿⣿⣶⣶⣶⣶⣤⣤⣤⣀⠄⠄⠄⠄⠄⠄⠄
⠄⠄⠄⢨⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠈⠻⣿⡛⠉⠭⠉⠉⢉⣿⣿⣧⠄⠄⠄⠄⠄
⠄⠄⠈⠙⠲⣶⠖⠄⠄⢿⣿⠄⠶⣶⣾⣿⣿⣿⣿⣧⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠈⠄⠄⠄⠺⢿⡗⠄⣹⣿⣿⠿⣟⣿⡏⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠤⠤⢾⣿⣿⣿⣦⠘⡿⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠈⢻⡿⣷⣶⣶⣤⣤⣤⣶⣦⠁⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⣽⣿⣿⣿⣿⣿⣿⣿⣿⡟⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠘⠿⣿⣿⣿⣿⣿⣿⣿⠃⠄⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠉⠛⠋⠉⠁⠄⠄⠄⠄⠄⠄⠄
 
 troll face


Our father, who AWPS in heaven
CS be thy game
Uncase begun, them skins be won,
Covert - and not a mil-spec
give us this day a StatTrak Knife
and forgive us when we rage quit,
as we forgive those who aimbot against us,
and lead us not into scamnation
but undeliverus a battlescarred
G A B E N .

⠄⠄⠁⣼⣷⣷⣴⣾⣶⣿⣾⣜⣾⡞⣼⣮⣶⡀⡀⠄⡀
⠄⣀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣻⣿⢷⠽⡹⡎⣆⠄⠄
⢐⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡕⠅⠂⢈⡪⡪⣂⠄
⠨⣺⡳⣿⢿⣿⣿⢿⢿⣿⡿⢿⠁⠁⠄⠄⢀⢿⢏⠆⠁
⢐⠬⠄⠂⠄⠄⠄⠈⠨⡲⠁⠄⠄⠄⠄⠄⠄⡱⣇⠇⢐
⠨⠄⠄⠄⠄⠄⠄⠄⣾⣿⣦⠄⠄⠄⠄⠄⠄⡜⣜⢌⠄
⠈⣷⡣⢤⣠⣤⢾⣺⣿⣿⣿⣵⣴⣠⣤⡸⡶⣟⢕⠡⡈
⠐⢐⠁⣗⡿⣿⡧⠎⠻⢿⠝⠷⢽⣿⣿⣾⡽⠄⢁⢇⢅
⠄⠂⠌⡋⣩⣾⣗⣦⣢⣱⣴⣷⣾⣿⡽⢿⡑⠄⢐⢌⠐
⠄⠂⠄⠄⠄⠄⠐⠉⠁⡉⡈⠉⠚⠛⠛⠂⠄⠄⡰⡁⠄
⠄⠄⠄⠄⠄⠄⣀⢀⢀⣀⢄⣅⢂⡁⠄⠄⠄⡠⡃⠄⠄
⠄⠄⠄⠄⡀⠄⣾⣾⣾⣿⣿⣿⣿⡶⠄⠠⠒⠅⢀⠄⠄
⠄⠄⠄⠄⠄⠄⠄⢘⢙⢻⢸⠱⠕⡁⠂⠈⠠⠁⡀⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠁⡠⠈⠈⡄⠌⠄⠄⠄ +rappp :Raelius:


⠀  ⠀⣠⣶⡾⠏⠉⠙⠳⢦⡀⠀⠀⠀⢠⠞⠉⠙⠲⡀⠀
⠀⠀⠀⣴⠿⠏⠀⠀⠀⠀⠀⠀⢳⡀⠀⡏⠀⠀⠀⠀⠀⢷
⠀⠀⢠⣟⣋⡀⢀⣀⣀⡀⠀⣀⡀⣧⠀⢸⠀⠀⠀⠀⠀ ⡇
⠀⠀⢸⣯⡭⠁⠸⣛⣟⠆⡴⣻⡲⣿⠀⣸⠀⠀OK⠀ ⡇
⠀⠀⣟⣿⡭⠀⠀⠀⠀⠀⢱⠀⠀⣿⠀⢹⠀⠀⠀⠀⠀ ⡇
⠀⠀⠙⢿⣯⠄⠀⠀⠀⢀⡀⠀⠀⡿⠀⠀⡇⠀⠀⠀⠀⡼
⠀⠀⠀⠀⠹⣶⠆⠀⠀⠀⠀⠀⡴⠃⠀⠀⠘⠤⣄⣠⠞⠀
⠀⠀⠀⠀⠀⢸⣷⡦⢤⡤⢤⣞⣁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⢀⣤⣴⣿⣏⠁⠀⠀⠸⣏⢯⣷⣖⣦⡀⠀⠀⠀⠀⠀⠀
⢀⣾⣽⣿⣿⣿⣿⠛⢲⣶⣾⢉⡷⣿⣿⠵⣿⠀⠀⠀⠀⠀⠀
⣼⣿⠍⠉⣿⡭⠉⠙⢺⣇⣼⡏⠀⠀⠀⣄⢸⠀⠀⠀⠀⠀⠀
⣿⣿⣧⣀⣿.........⣀⣰⣏⣘⣆⣀⠀⠀


⠄⠄⢀⣀⣤⣤⣴⣶⣶⣶⣶⣶⣶⣶⣶⣶⣶⣤⣤⣄⣀⠄⠄
⠄⠠⣿⢿⣿⢿⣯⣿⣽⢯⣟⡿⣽⢯⣿⣽⣯⣿⣽⣟⣟⣗⠄
⠄⢸⡻⠟⡚⡛⠚⠺⢟⣿⣗⣿⢽⡿⡻⠇⠓⠓⠓⠫⢷⢳⠄
⠄⢼⡺⡽⣟⡿⣿⣦⡀⡈⣫⣿⡏⠁⢀⣰⣾⢿⣟⢟⢮⢱⡀
⠄⣳⠑⠝⠌⠊⠃⠃⢏⢆⣺⣿⣧⢘⠎⠋⠊⠑⠨⠣⠑⣕⠂
⠄⢷⣿⣯⣦⣶⣶⣶⡶⡯⣿⣿⡯⣟⣶⣶⣶⣶⣦⣧⣷⣾⠄
⠄⢹⢻⢯⢟⣟⢿⢯⢿⡽⣯⣿⡯⣗⡿⡽⡯⣟⡯⣟⠯⡻⠂
⠄⠢⡑⡑⠝⠜⣑⣭⠻⢝⠿⡿⡯⠫⠯⣭⣊⠪⢊⠢⢑⠰⠁
⠄⠈⢹⣔⡘⢿⣿⣿⣶⠄⠁⠑⠈⠠⣵⣿⡿⡯⠂⣠⡞⡈⠄
⠄⠄⠨⢻⡆⢄⣀⢩⠄⠄⠴⠕⠄⠄⠈⠉⣀⠠⢢⡟⢌⠄⠄
⠄⠄⠈⠐⡝⣧⠈⡉⡙⢛⠛⠛⠛⠛⢋⠉⡀⡼⠩⡂⠁⠄⠄
⠄⠄⠄⠄⠈⠪⡻⣔⣮⣷⡆⠄⢰⣿⢦⣣⢞⠅⠁⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠄⠈⠓⣷⣿⡅⠄⢸⣿⡗⠇⠁⠄⠄⠄⠄⠄⠄

⠄⠄⠄⠄⠄⠐⠄⢀⢀⢘⣴⣲⣶⣦⣕⠆⠤⠄⠄⠈
⠄⠄⠄⠃⢀⢠⢦⣻⢽⢯⡿⣽⣻⢾⢽⡽⡬⡄⠄⠄⡀
⠄⠄⠄⠄⠂⢽⢝⢮⢫⡳⡻⡽⡽⡝⣗⢟⡯⣯⢵⠐⠄
⠄⠄⠄⠄⠄⠈⡲⡱⡱⡱⡡⣣⣣⢝⣜⣗⢯⠺⢅⠐⡇
⠄⠄⠄⠄⠄⡂⡢⢯⢗⡮⠚⠗⠋⠟⠳⠻⢇⣗⠄⡨⡒
⠄⠄⠄⠄⠄⠈⠄⠁⠁⣵⣄⠄⠄⠄⠂⣀⡤⣷⠱⣌⡇
⠄⠄⠄⠄⠄⠄⢀⢠⠄⣿⣿⣳⣦⣖⣟⢯⢿⡱⡭⡪⠃
⠄⠄⠄⠄⠄⠐⢕⢇⠄⣾⢿⣞⢮⢺⣺⣕⢧⢯⢯
⠄⡌⣢⢿⣆⠄⠐⡁⠄⠄⢁⣰⢹⠳⣜⡾⡽⡕⣏⣄
⢧⣥⣟⠟⠛⡀⢑⠄⠄⢀⣈⣥⡭⣥⣕⢟⢗⠕⢌⣿⠄
⣶⣌⠿⢧⠫⢿⣀⠄⠠⢀⢀⣠⡨⣌⢎⠄⢁⣶⡿⠄⠄⠄
⢙⢻⣦⠄⡯⡇⠄⠄⠄⠄⡁⡑⠌⠊⠄⢠⠟⠉⠄⣴⠄⠄
⠄⢣⠄⣀⢑⠇⠄⠄⢀⠄⠠⠄⠄⠄⠐⠉⠄⠄⠄⠁⠄⠐
⢘⣼⣻⣮⡿⠄⠄⠄⠄⠄⠄⡀⡀⡄⣄⢶⠶⡻⣻⠏⠄⠈


⢠⠊⣉⠒⠤⢀⡀          ⡐⢁⠴⢜⢄
 ⡎⢸  ⠉⠐⠢⢌⠑⢄    ⡸  ⡆    ⠣⠱⡀
  ⡇⢸        ⣀⠗  ⠉⠉⠁  ⠙⠢⠤⡀⢃⢱
 ⡇⠘⣄⢀⠔⠉                    ⠈⠁⠘⡄
 ⢇    ⠁                              ⠘⡄
  ⢸            ⢀⣀⣀⡀        ⢀⣀⣀⡀  ⢣
 ⡸        ⢴⣾⡿⠿⠽⠇        ⠘⠛⠛⠛  ⠈⢄
⠰⡁              ⢠⠒⠢⡀⠈⠒⠊  ❤ ⡠⢄  ⡘
 ⠱⣀          ⢀⠜    ⠇        ⢀⠔⠁  ⡏
     ⠑⠤⢄⣀⠔⠁    ⡜        ⠊⠁  ⢀⠜

⊂_ヽ
　 ＼＼ ＿
　　 ＼(　•_•)
　　　 <　⌒ヽ+
　　　/ 　 へ＼ R
　　 /　　/　＼＼ E
　　 ﾚ　ノ　　 ヽ_つP
　　/　/
　 /　/|
　(　(ヽ
　|　|、＼
　| 丿 ＼ ⌒)
　| |　　) /
`ノ )　　Lﾉ



.......................___,,...,,__　／`''/`i
　　|``~--,...~```　　　　　``　＊ |
　　i ヽ　　　　　　　　　　　:;
　　\　彡　　　　 　　　　　　ミ
　　〉　　　　●　　.　　●　　　ミ
　　彡　 　 ``　　　人　　```　　　ミ
　 彡:　　　　　 　　　　 　　　 　ミ
,︵I:　　　　　　つ:+REP:⌒　　　　ミ
r,_,.::::　　　 　　　　　　　　　　ミ
　 ヽ川:::::::　　　　　　　　　　;;
　　 ゞ..;;;;;;;__,.╰╯::::::╰╯::::＊

⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠄
⣦⣌⣛⣻⣿⣿⣧⠙⠛⠛⡭⠅⠒⠦⠭⣭⡻⣿⣿⣿⣿⣿⣿⣿⣿⡿⠃⠄
⣿⣿⣿⣿⣿⣿⣿⡆⠄⠄⠄⠄⠄⠄⠄⠄⠹⠈⢋⣽⣿⣿⣿⣿⣵⣾⠃⠄
⣿⣿⣿⣿⣿⣿⣿⣿⠄⣴⣿⣶⣄⠄⣴⣶⠄⢀⣾⣿⣿⣿⣿⣿⣿⠃⠄⠄
⠈⠻⣿⣿⣿⣿⣿⣿⡄⢻⣿⣿⣿⠄⣿⣿⡀⣾⣿⣿⣿⣿⣛⠛⠁⠄⠄⠄
⠄⠄⠈⠛⢿⣿⣿⣿⠁⠞⢿⣿⣿⡄⢿⣿⡇⣸⣿⣿⠿⠛⠁⠄⠄⠄⠄⠄
⠄⠄⠄⠄⠄⠉⠻⣿⣿⣾⣦⡙⠻⣷⣾⣿⠃⠿⠋⠁⠄⠄⠄⠄⠄⢀⣠⣴
⣿⣶⣶⣮⣥⣒⠲⢮⣝⡿⣿⣿⡆⣿⡿⠃⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⣠


MAGIA DO GATINHO
. ∧＿∧　
（｡･ω･｡)つ━☆・*。
⊂　　 ノ 　　　・゜+.
　しーＪ　　　°。+ *´¨)
　　　　　　　　　.• ´¸.•*´¨) ¸.•*¨)
　　　　　　　　　　(¸.•´ (¸.•'* ☆ PRA PARAR DE SER NOOBZINHO

COLE ISSO NO PERFIL DO SEU AMIGUINHO
QUE PRECISA DE MAIS DEDINHO


⠄⠄⣿⣿⣿⣿⠘⡿⢛⣿⣿⣿⣿⣿⣧⢻⣿⣿⠃⠸⣿⣿⣿⠄⠄⠄⠄⠄
⠄⠄⣿⣿⣿⣿⢀⠼⣛⣛⣭⢭⣟⣛⣛⣛⠿⠿⢆⡠⢿⣿⣿⠄⠄⠄⠄⠄
⠄⠄⠸⣿⣿⢣⢶⣟⣿⣖⣿⣷⣻⣮⡿⣽⣿⣻⣖⣶⣤⣭⡉⠄⠄⠄⠄⠄
⠄⠄⠄⢹⠣⣛⣣⣭⣭⣭⣁⡛⠻⢽⣿⣿⣿⣿⢻⣿⣿⣿⣽⡧⡄⠄⠄⠄
⠄⠄⠄⠄⣼⣿⣿⣿⣿⣿⣿⣿⣿⣶⣌⡛⢿⣽⢘⣿⣷⣿⡻⠏⣛⣀⠄⠄
⠄⠄⠄⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⠙⡅⣿⠚⣡⣴⣿⣿⣿⡆⠄
⠄⠄⣰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⠄⣱⣾⣿⣿⣿⣿⣿⣿⠄
⠄⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠣⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄
⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠑⣿⣮⣝⣛⠿⠿⣿⣿⣿⣿⠄
⢠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⠄⠄⠄⠄⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠄
YOU'VE BEEN VISITED BY THE HOLY BUTCHEEKS

http://steamcommunity.com/profiles/76561198799183883 >> her

⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣷⣜⢿⣧⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡄⠻⣿⣿⣿⣿⣦⠄⠄
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣮⡻⣷⡙⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣆⠙⣿⣿⣿⣿⣧⠄
⣿⣿⣿⣿⣿⣿⣿⣿⣿⠏⣿⣿⣿⣿⣿⣿⣧⢸⣿⣿⣿⡘⢿⣮⡛⣷⡙⢿⣿⡏⢻⣿⣿⣿⣧⠙⢿⣿⣿⣷⠘⢿⣿⣆⢿⣿⣿⣿⣿⣆
⣿⣿⣿⣿⣿⣿⣿⣿⡿⠐⣿⣿⣿⣿⣿⣿⠃⠄⢣⠻⣿⣧⠄⠙⢷⡀⠙⢦⡙⢿⡄⠹⣿⣿⣿⣇⠄⠻⣿⣿⣇⠈⢻⣿⡎⢿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⣿⣿⣿⣿⣿⠋⠄⣼⣆⢧⠹⣿⣆⠄⠈⠛⣄⠄⢬⣒⠙⠂⠈⢿⣿⣿⡄⠄⠈⢿⣿⡀⠄⠙⣿⠘⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⣿⣿⣿⣿⠏⢀⣼⣿⣿⣎⠁⠐⢿⠆⠄⠄⠈⠢⠄⠙⢷⣤⡀⠄⠙⠿⠷⠄⠄⠄⠹⠇⠄⠄⠘⠄⢸⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⢻⣿⣿⠏⢀⣾⣿⣿⣿⣿⡦⠄⠄⡘⢆⠄⠄⠄⠄⠄⠄⠙⠻⡄⠄⠄⠉⡆⠄⠄⠄⠑⠄⢠⡀⠄⠄⣿⡿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⢸⣿⠋⣰⣿⣿⡿⢟⣫⣵⣾⣷⡄⢻⣄⠁⠄⠄⠠⣄⠄⠄⠄⠈⠂⠄⠄⠈⠄⠱⠄⠄⠄⠄⢷⢀⣠⣽⡇⣿
⣿⣿⣿⣿⣿⣿⣿⣿⡄⠄⠄⢁⣚⣫⣭⣶⣾⣿⣿⣿⣿⣿⣿⣦⣽⣷⣄⠄⠄⠘⢷⣄⠄⠄⠄⠄⣠⠄⠄⠄⠄⠈⠉⠈⠻⢸⣿⣿⡇⣿
⣿⣿⣿⣿⣿⣿⣿⣿⡇⠄⢠⣾⣿⣿⣿⣿⣿⡿⠿⠿⠟⠛⠿⣿⣿⣿⣿⣷⣤⣤⣤⣿⣷⣶⡶⠋⢀⡠⡐⢒⢶⣝⢿⡟⣿⢸⣿⣿⡃⣿
⣿⣿⣿⢹⣿⢿⣿⣿⣷⢠⣿⣿⣿⣿⣯⠷⠐⠋⠋⠛⠉⠁⠛⠛⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⡀⡏⠊⡼⢷⢱⣿⡾⡷⣿⢸⡏⣿⢰⣿
⣿⣿⣿⢸⣿⡘⡿⣿⣿⠎⣿⠟⠋⢁⡀⡠⣒⡤⠬⢭⣖⢝⢷⣶⣬⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⢃⢔⠭⢵⣣⣿⠓⢵⣿⢸⢃⡇⢸⣿
⣿⣿⣿⡄⣿⡇⠄⡘⣿⣷⡸⣴⣾⣿⢸⢱⢫⡞⣭⢻⡼⡏⣧⢿⣿⣿⣿⣿⣿⣿⣿⡿⣿⢿⡿⣿⣧⣕⣋⣉⣫⣵⣾⣿⡏⢸⠸⠁⢸⡏
⣿⣿⣿⡇⠸⣷⠄⠈⠘⢿⣧⠹⣹⣿⣸⡼⣜⢷⣕⣪⡼⣣⡟⣾⣿⣿⢯⡻⣟⢯⡻⣿⣮⣷⣝⢮⣻⣿⢿⣿⣝⣿⣿⢿⣿⢀⠁⠄⢸⠄
⣿⣿⡿⣇⠄⠹⡆⠄⠄⠈⠻⣧⠩⣊⣷⠝⠮⠕⠚⠓⠚⣩⣤⣝⢿⣿⣯⡿⣮⣷⣿⣾⣿⢻⣿⣿⣿⣾⣷⣽⣿⣿⣿⣿⡟⠄⠄⠄⠄⢸
⠹⣿⡇⢹⠄⠄⠐⠄⠄⠄⠄⠈⠣⠉⡻⣟⢿⣝⢿⣝⠿⡿⣷⣝⣷⣝⣿⣿⣿⣿⣿⣿⣿⣧⢹⣿⣿⣿⣿⣿⣿⣿⣿⡟⣠⠄⠄⠄⠄⠈
⠄⠘⠇⠄⠄⠄⠄⠄⠄⠄⠄⠄⠠⣌⠈⢳⢝⣮⣻⣿⣿⣮⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠄⠄⠄⠄⢀
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢻⣷⣤⣝⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠇⠄⠄⠄⠄⣼
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⢿⣿⣿⣿⣿⣿⣿⣿⠏⠄⠄⠄⠄⣰⢩
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢻⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⠛⠋⠉⠉⠉⠄⠄⠄⠄⣸⣿⣿⣿⣿⡿⠃⠄⠄⠄⠄⣰⣿⣧
⣷⡀⠄⠈⢦⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⢻⣯⣿⣿⣿⣿⣿⣿⣿⣿⣷⣤⣤⣤⣶⣶⣶⣶⣾⣿⣿⣿⣿⡿⠋⠄⠄⠄⠄⠄⣰⣿⣿⣿
⣿⣿⣦⡱⣌⢻⣦⡀⠄⠄⠄⠄⠄⠄⠄⠄⠄⠙⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠋⠄⠄⠄⠄⠄⠄⢰⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣷⣿⣿⣦⣐⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠛⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣫⡔⢀⣴⠄⠄⠄⡼⣠⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⠏⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠉⠉⠉⠙⠛⢛⣛⣛⣭⣾⣿⣴⣿⢇⣤⣦⣾⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⠟⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠈⠛⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿

uwu girl 
⢕⢕⢕⢕⠁⢜⠕⢁⣴⣿⡇⢓⢕⢵⢐⢕⢕⠕⢁⣾⢿⣧⠑⢕⢕⠄⢑⢕⠅⢕
⢕⢕⠵⢁⠔⢁⣤⣤⣶⣶⣶⡐⣕⢽⠐⢕⠕⣡⣾⣶⣶⣶⣤⡁⢓⢕⠄⢑⢅⢑
⠍⣧⠄⣶⣾⣿⣿⣿⣿⣿⣿⣷⣔⢕⢄⢡⣾⣿⣿⣿⣿⣿⣿⣿⣦⡑⢕⢤⠱⢐
⢠⢕⠅⣾⣿⠋⢿⣿⣿⣿⠉⣿⣿⣷⣦⣶⣽⣿⣿⠈⣿⣿⣿⣿⠏⢹⣷⣷⡅⢐
⣔⢕⢥⢻⣿⡀⠈⠛⠛⠁⢠⣿⣿⣿⣿⣿⣿⣿⣿⡀⠈⠛⠛⠁⠄⣼⣿⣿⡇⢔
⢕⢕⢽⢸⢟⢟⢖⢖⢤⣶⡟⢻⣿⡿⠻⣿⣿⡟⢀⣿⣦⢤⢤⢔⢞⢿⢿⣿⠁⢕
⢕⢕⠅⣐⢕⢕⢕⢕⢕⣿⣿⡄⠛⢀⣦⠈⠛⢁⣼⣿⢗⢕⢕⢕⢕⢕⢕⡏⣘⢕
⢕⢕⠅⢓⣕⣕⣕⣕⣵⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣷⣕⢕⢕⢕⢕⡵⢀⢕⢕
⢑⢕⠃⡈⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢃⢕⢕⢕

░░█░░░█▀█░█▀▀░█▀█
▀▀█▀▀░█▀▄░█▀░░█▀▀
░░█░░░▀░▀░▀▀▀░▀░░
／ﾌﾌ 　　　　　　　ム｀ヽ
/ ノ) 　　　　　　　　）　ヽ
/ ｜　　( ͡° ͜ʖ ͡°）ノ⌒（ゝ._,ノ
/　ﾉ⌒7⌒ヽーく　 ＼　／
丶＿ ノ ｡　　 ノ､　｡|/
　　 `ヽ `ー-'_人`ーﾉ
　　　 丶 ￣ _人'彡ﾉ
   
   
⠄⠄⠄⠄⠄⠐⠄⢀⢀⢘⣴⣲⣶⣦⣕⠆⠤⠄⠄⠈
⠄⠄⠄⠃⢀⢠⢦⣻⢽⢯⡿⣽⣻⢾⢽⡽⡬⡄⠄⠄⡀
⠄⠄⠄⠄⠂⢽⢝⢮⢫⡳⡻⡽⡽⡝⣗⢟⡯⣯⢵⠐⠄
⠄⠄⠄⠄⠄⠈⡲⡱⡱⡱⡡⣣⣣⢝⣜⣗⢯⠺⢅⠐⡇
⠄⠄⠄⠄⠄⡂⡢⢯⢗⡮⠚⠗⠋⠟⠳⠻⢇⣗⠄⡨⡒
⠄⠄⠄⠄⠄⠈⠄⠁⠁⣵⣄⠄⠄⠄⠂⣀⡤⣷⠱⣌⡇
⠄⠄⠄⠄⠄⠄⢀⢠⠄⣿⣿⣳⣦⣖⣟⢯⢿⡱⡭⡪⠃
⠄⠄⠄⠄⠄⠐⢕⢇⠄⣾⢿⣞⢮⢺⣺⣕⢧⢯⢯
⠄⡌⣢⢿⣆⠄⠐⡁⠄⠄⢁⣰⢹⠳⣜⡾⡽⡕⣏⣄
⢧⣥⣟⠟⠛⡀⢑⠄⠄⢀⣈⣥⡭⣥⣕⢟⢗⠕⢌⣿⠄
⣶⣌⠿⢧⠫⢿⣀⠄⠠⢀⢀⣠⡨⣌⢎⠄⢁⣶⡿⠄⠄⠄
⢙⢻⣦⠄⡯⡇⠄⠄⠄⠄⡁⡑⠌⠊⠄⢠⠟⠉⠄⣴⠄⠄
⠄⢣⠄⣀⢑⠇⠄⠄⢀⠄⠠⠄⠄⠄⠐⠉⠄⠄⠄⠁⠄⠐
⢘⣼⣻⣮⡿⠄⠄⠄⠄⠄⠄⡀⡀⡄⣄⢶⠶⡻⣻⠏⠄⠈
godfather

⠄⠄⠁⣼⣷⣷⣴⣾⣶⣿⣾⣜⣾⡞⣼⣮⣶⡀⡀⠄⡀
⠄⣀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣻⣿⢷⠽⡹⡎⣆⠄⠄
⢐⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡕⠅⠂⢈⡪⡪⣂⠄
⠨⣺⡳⣿⢿⣿⣿⢿⢿⣿⡿⢿⠁⠁⠄⠄⢀⢿⢏⠆⠁
⢐⠬⠄⠂⠄⠄⠄⠈⠨⡲⠁⠄⠄⠄⠄⠄⠄⡱⣇⠇⢐
⠨⠄⠄⠄⠄⠄⠄⠄⣾⣿⣦⠄⠄⠄⠄⠄⠄⡜⣜⢌⠄
⠈⣷⡣⢤⣠⣤⢾⣺⣿⣿⣿⣵⣴⣠⣤⡸⡶⣟⢕⠡⡈
⠐⢐⠁⣗⡿⣿⡧⠎⠻⢿⠝⠷⢽⣿⣿⣾⡽⠄⢁⢇⢅
⠄⠂⠌⡋⣩⣾⣗⣦⣢⣱⣴⣷⣾⣿⡽⢿⡑⠄⢐⢌⠐
⠄⠂⠄⠄⠄⠄⠐⠉⠁⡉⡈⠉⠚⠛⠛⠂⠄⠄⡰⡁⠄
⠄⠄⠄⠄⠄⠄⣀⢀⢀⣀⢄⣅⢂⡁⠄⠄⠄⡠⡃⠄⠄
⠄⠄⠄⠄⡀⠄⣾⣾⣾⣿⣿⣿⣿⡶⠄⠠⠒⠅⢀⠄⠄
⠄⠄⠄⠄⠄⠄⠄⢘⢙⢻⢸⠱⠕⡁⠂⠈⠠⠁⡀⠄⠄
⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠄⠁⡠⠈⠈⡄⠌⠄⠄⠄

▒▒▒░░░░░░░░░░▄▐░░░░
▒░░░░░░▄▄▄░░▄██▄░░░
░░░░░░▐▀█▀▌░░░░▀█▄░
░░░░░░▐█▄█▌░░░░░░▀█▄
░░░░░░░▀▄▀░░░▄▄▄▄▄▀▀
░░░░░▄▄▄██▀▀▀▀░░░░░
░░░░█▀▄▄▄█░▀▀░░░░░░
░░░░▌░▄▄▄▐▌▀▀▀░░░░░
░▄░▐░░░▄▄░█░▀▀░░░░░
░▀█▌░░░▄░▀█▀░▀░░░░░
░░░░░░░░▄▄▐▌▄▄░░░░░
░░░░░░░░▀███▀█░▄░░░
░░░░░░░▐▌▀▄▀▄▀▐▄░░░
░░░░░░░▐▀░░░░░░▐▌░░
░░░░░░░█░░░░░░░░█░░
░░░░░░▐▌░░░░░░░░░█░
    
⠀⠀⠀⠀⠀⠀⣀⠤⠤⠖⠒⠒⠒⠤⣀
⣀⣀⣀⡠⠔⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠑⢤
⠀⠉⢒⠀⠀⢀⣦⠖⡟⣠⠋⢦⠀⡀⠀⠀⠀⣀⠀⠈⣄
⠀⣴⠁⠀⣴⠁⠀⠀⠁⠀⠀⠀⠉⠈⣤⡀⠀⣿⠀⢳⡄⡄
⢣⢣⠀⣼⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢳⣿⠀⢸⣾⣿⠁⢹
⠀⢸⢴⢙⣠⡖⡲⡀⠀⠀⠀⢀⠴⡶⣌⢸⠀⠀⡏⠀⠀⡆
⠀⡞⠀⡃⢹⣿⣻⠈⠀⠀⠀⠋⢺⡫⢷⢻⠀⠀⡇⠀⠀⢸
⠀⡇⠀⠇⠸⣝⡿⠀⠀⠀⠀⠈⣬⣿⣾⢸⠀⠀⡇⠀⠀⠀⢸
⢀⠀⣯⠀⠀⠀⠀⠀⣀⣀⠄⠀⠀⠁⠀⡾⣹⠄⡇⠀⠀⠀⢸
⢸⠀⠀⣦⣾⣿⣦⣴⣾⣦⣴⣾⣷⣄⡤⡇⠀⠀⡇⠀⠀⠀⡄
⡜⠀⠀⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠀⢀⡿⠀⠀⠀⠘⡀
⡇⠀⠀⠀⡟⠁⠈⠛⠁⠈⠚⠉⠀⠈⠏⠀⠀⡼⠀⠀⠀⠀⠀⠀⢱
⢳⠀⠀⢀⠃⠀⠀⢸⣿⣷⠀⠀⠀⢰⠀⠀⣰⢷⠀⠀⠀⠀⠀⠀⣸
Have a sad day    
    

rick astley simp
..................„-~~'''''''~~--„„_
.............„-~''-,::::::::::::::::::: ''-„
.........,~''::::::::',:::::::::::::::: ::::|',
.........::::::,-~'''¯¯¯''''~~--~'''¯'''-,:|
........'|:::::|: : : : : : : : : : : ::: : |,'
........|:::::|: : :-~~---: : : -----: |
.......(¯''~-': : : :'¯0: ',: :|: :0-: :/
.....'....''~-,|: : : : : : ~---': : : :,'
...............|,: : : : : :-~~--: : ::/ FOLKS, I THINK IT'S OBVIOUS.
......,-''\':\: :'~„„_: : : : : _,-' HE IS A SIMP.
__„-';;;;;\:''-,: : : :'~---~''/|
;;;;;/;;;;;;;\: :\: : :____/: :',__
;;;;;;;;;;;;;;',. .''-,:|:::::::|. . |;;;;''-„__
;;;;;;,;;;;;;;;;\. . .''|::::::::|. .,';;;;;;;;;;''-„
;;;;;;;|;;;;;;;;;;;\. . .\:::::,'. ./|;;;;;;;;;;;;;|
;;;;;;;\;;;;;;;;;;;',: : :|¯¯|. . .|;;;;;;;;;,';;|
;;;;;;;;;',;;;;;;;;;;;\. . |:::|. . .'',;;;;;;;;|;;/
;;;;;;;;;;\;;;;;;;;;;;\. .|:::|. . . |;;;;;;;;|/
;;;;;;;;;;;;,;;;;;;;;;;|. .\:/. . . .|;;;;;;;;

cat glyph 2 
 .,,..;~`''''　　　　`''''＜``彡　}
　 _...:=,`'　　 　︵　 т　︵　　X彡-J
＜`　彡 /　　ミ　　,_人_.　＊彡　`~
　 `~=::　　　 　　　　　　 　　　Y
　　 　i.　　　　　　　　　　　　 .:
　　　.\　　　　　　　,｡---.,,　　./
　　　　ヽ　／ﾞ''```\;.{　　　 ＼／
　　　　　Y　　　`J..r_.彳　 　|　　 𝓗𝓪𝓿𝓮 𝓪 𝓷𝓲𝓬𝓮 𝓭𝓪𝔂! :kalove::kalove::kalove:
　　　　　{　　　``　　`　　　i
　　　　　\　　　　　　　　　＼　　　..︵︵.
　　　　　`＼　　　　　　　　　``ゞ.,/` oQ o`)
　　　　　　`i,　　　　　　　　　　Y　 ω　/
　　　　 　　`i,　　　 　　.　　　　"　　　/
　　　　　　`iミ　　　　　　　　　　　,,ノ
　　　　 　 ︵Y..︵.,,　　　　　,,+..__ノ``
　　　　　(,`, З о　　　　,.ノ
　　　　　 ゞ_,,,....彡彡~

Dog 
╭━━━╮     ╭━━━╮
┃╭┈┈╰━━━╯┈┈╮    ┃
╰┓╭━━╮ ╭━━╮   ┏╯
 ┃┃╭╮┃ ┃╭╮┃  ┃
 ┃╰┻┻╯▃╰┻┻╯  ┃
 ┃   ╰━╯  ┃
 ╰━┓    ┏━╯
   ┃┈╮ ╭┈┃
   ┃╰╯ ╰╯┃
   ╰┓┏━┓┏╯
    ╰╯ ╰╯ 
    dfog

⣿⣿⣿⡇⢩⠘⣴⣿⣥⣤⢦⢁⠄⠉⡄⡇⠛⠛⠛⢛⣭⣾⣿⣿⡏
⣿⣿⣿⡇⠹⢇⡹⣿⣿⣛⣓⣿⡿⠞⠑⣱⠄⢀⣴⣿⣿⣿⣿⡟
⣿⣿⣿⣧⣸⡄⣿⣪⡻⣿⠿⠋⠄⠄⣀⣀⢡⣿⣿⣿⣿⡿⠋
⠘⣿⣿⣿⣿⣷⣭⣓⡽⡆⡄⢀⣤⣾⣿⣿⣿⣿⣿⡿⠋
⠄⢨⡻⡇⣿⢿⣿⣿⣭⡶⣿⣿⣿⣜⢿⡇⡿⠟⠉
⠄⠸⣷⡅⣫⣾⣿⣿⣿⣷⣙⢿⣿⣿⣷⣦⣚⡀
⠄⠄⢉⣾⡟⠙(PRO)⣷⣅⢻⣿⣿⣿⣿⣿⣶⣶⡆⠄⣤⡀
⠄⢠⣿⣿⣧⣀⣀⣀⣀⣼⣿⣿⣿⡎⢿⣿⣿⣿⣿⣿⣿⣇(PRO)
⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢇⣎⢿⣿⣿⣿⣿⣿⣿⣿⣶⣶
⠄⠄⠻⢿⣿⣿⣿⣿⣿⣿⣿⢟⣫⣾⣿⣷⡹⣿⣿⣿⣿⣿⣿⣿⡟
⠄⠄⠄⠄⢮⣭⣍⡭⣭⡵⣾⣿⣿⣿⡎⣿⣿⣌⠻⠿⠿⠿⠟⠋
⠄⠄⠄⠄⠈⠻⣿⣿⣿⣿⣹⣿⣿⣿⡇⣿⣿⡿
⠄⠄⣀⣴⣾⣶⡞⣿⣿⣿⣿⣿⣿⣿⣾⣿⡿⠃
⣠⣾⣿⣿⣿⣿⣿⣹⣿⣿⣿⣿⣿⡟⣹⣿⣳⡄xd

⣿⣿⡇⣿⣿⣏⣿⣿⣿⣮⣻⣾⣿⣿⡿⣿⣧⡻⠛⣯⣙⠒⣧⣽⣿⣶⣿⣿⣿⣿
⣿⣿⣷⣿⡿⣼⣿⣿⣿⣿⣿⡵⣻⣿⣧⣿⣿⣿⣮⡻⣿⠄⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣸⣧⠿⠟⢿⣿⣿⣿⣿⣦⠻⣿⣻⣿⣿⣿⣿⣮⣀⢿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⠏⣿⢡⣤⣤⣤⣈⠛⢿⣿⢿⣷⣝⣫⢿⣿⣿⣿⣿⣿⣷⣭⣟⡿⢿⣻⣯⣵
⣿⣿⡆⣏⢸⣿⣿⣿⣿⣷⣦⡈⣷⣽⣿⣯⡊⢿⣿⣿⣿⣿⣿⣭⣵⣶⣷⣝⡻⣿
⣿⣿⣷⣻⣼⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⣿⣾⣿⣿⡿⠋⠛⣋⣉⡉⠙⣿⣫⣾
⣿⣿⣿⣯⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣾⣿⣿⣿⣿⣗⣵⣿⣿
⠈⢿⣿⣿⣹⣿⣿⣿⡿⠟⠋⠉⠉⠛⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣼⣿⣿⡟
⠄⠄⠹⣿⣷⢻⣿⢏⣶⣶⣶⣶⣶⣶⣦⡄⡀⠄⢹⣿⣿⣿⣿⣿⣿⣇⣿⣿⣿⠃
⣄⠄⠄⠄⠻⣧⢙⡺⢿⣿⣿⣿⣿⣿⣿⣿⣿⢇⣾⣿⣿⣿⣿⡿⣫⣾⣿⣿⡏
⣷⣿⡿⢿⣿⣾⡥⢮⢪⣏⠿⠻⠻⠟⠛⠟⠯⠾⠿⠿⠛⠋⢱⣿⣿⣿⣿⣿⠁

░█▀▀▄░░░░░░░░░░░▄▀▀█
░█░░░▀▄░▄▄▄▄▄░▄▀░░░█
░░▀▄░░░▀░░░░░▀░░░▄▀
░░░░▌░▄▄░░░▄▄░▐▀▀
░░░▐░░█▄░░░▄█░░▌▄▄▀▀▀▀█
░░░▌▄▄▀▀░▄░▀▀▄▄▐░░░░░░█ Have a nice day!
▄▀▀▐▀▀░▄▄▄▄▄░▀▀▌▄▄▄░░░█
█░░░▀▄░█░░░█░▄▀░░░░█▀▀▀
░▀▄░░▀░░▀▀▀░░▀░░░▄█▀
░░░█░░░░░░░░░░░▄▀▄░▀▄
░░░█░░░░░░░░░▄▀█░░█░░█
░░░█░░░░░░░░░░░█▄█░░▄▀
░░░█░░░░░░░░░░░████▀
░░░▀▄▄▀▀▄▄▀▀▄▄▄█▀

pika pika he is chutiya rep+

█▀▀░█░█░█▀█░█▀▀░█▀█░░░
▀▀█░█░█░█▀▀░█▀░░█▀▄░░░
▀▀▀░▀▀▀░▀░░░▀▀▀░▀░▀░░░
█▄░▄█░█▀▀░█▀▀▀░ █▀█░░░
█░█░█░█▀░░█░▀█░█▀▀█░░░
▀░▀░▀░▀▀▀░▀▀▀▀░▀░░▀░░░
█░░█░█░▀▀█▀▀░█▀█░ █▀█░
█░░█░█░░░█░░░█▀▄░█▀▀█░
▀▀▀▀░▀▀▀░▀░░░▀░▀░▀░░▀░
░░░░█▀▀░█▀█░█░█▀▀░░░░
░░░░█▀░░█▀▀░█░█░░░░░░
░░░░▀▀▀░▀░░░▀░▀▀▀░░░░
░░░█░░░█▀█░█▀▀░█▀█░░░
░▀▀█▀▀░█▀▄░█▀░░█▀▀░░░
░░░█░░░▀░▀░▀▀▀░▀░░░░


Cat Glyph 
⠀⠀⠀⠀⠀⠀⠀⢀⣠⠤⠶⠒⠚⠛⠓⢲⣶⡤
⠀⠀⠀⠀⢀⡴⠚⠁⠁⠁⠁⣁⠵⠛⠉⠁⠀⠀⠀⠀★
⠀⠀⢀⣴⠁⠁⠁⠁⠁⢁⡞⠁
⠀⢠⡞⠁⠁⠁⠁⠁⢁⠏⠀⠀
⢀⡾⠁⠁⠁⠁⠁⢁⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⠀⠀⠀⠀⢠⡿
⣼⠁⠁⠁⠁⠁⠁⣹⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣿⣿⣶⡄⣰⣿
⣿⠁⠁⠁⠁⠁⠁⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⠏
⣿⠁⠁⠁⠁⠁⠁⢻⡄⠀⠀⠀⣴⠿⢿⣆⠀⢀⣴⣿⣿⣿⣿⠃
⢻⠁⠁⠁⠁⠁⠁⠉⣷⡀⠀⠀⣿⠀⠾⠏⣴⣿⣿⣿⣿⣿⡟
⠈⢧⠁⠁⠁⠁⠁⠁⠉⠷⣄⠀⠹⡄⠀⠀⣿⣿⣿⣿⣿⣿⡇
⠀⠘⢆⠁⠁⠁⠁⠁⠁⠁⠉⠳⣄⠹⣦⡀⢿⣿⣿⣿⣿⣿⡇
⠀⠀⠈⢳⡁⠁⠁⠁⠁⠁⠁⠁⠉⠙⠶⡿⣿⣿⣿⣿⣿⣿⠷
⠀⠀⠀⠀⠉⠳⣅⠁⠁⠁⠁⠁⠁⠁⠁⠁⠁⠁⠁⣁⡥⠛⠁
⠀⠀⠀⠀⠀⠀⠀⠉⠓⠳⢧⣥⣥⣥⡥⠥⠵⠛⠋⠁⠀


𝓱𝓪𝓿𝓮 𝓪 𝓰𝓻𝓮𝓪𝓽 𝓭𝓪𝔂!

____🐸🐸🐸🐸____🐸🐸🐸
___🐸🐸🐸🐸🐸__🐸🐸🐸🐸
__🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸
🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸
🐸🐸⚪⚫⚫⚪🐸🐸🐸⚪⚫⚫⚪
🐸⚪⚫⚫⚪⚫⚪🐸⚪⚫⚫⚪⚫⚪
🐸⚪⚫⚪⚫⚫⚪🐸⚪⚫⚪⚫⚫⚪
🐸🐸⚪⚫⚪⚪🐸🐸🐸⚪⚫⚪⚪
🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸
🔴🔴🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸
🐸🔴🔴🐸🐸🐸🐸🐸🐸🐸🐸🐸
🐸🐸🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴
🐸🐸🐸🔴🔴🔴🔴🔴🔴🔴🔴🔴🔴
🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸
🐸🐸🐸🐸🐸🐸🐸🐸🐸🐸
🐸🐸🐸🐸🐸🐸🐸🐸🐸

░░░░░░░░░░░█▀▀░░█░░░░░░
░░░░░░▄▀▀▀▀░░░░░█▄▄░░░░
░░░░░░█░█░░░░░░░░░░▐░░░
░░░░░░▐▐░░░░░░░░░▄░▐░░░
░░░░░░█░░░░░░░░▄▀▀░▐░░░
░░░░▄▀░░░░░░░░▐░▄▄▀░░░░
░░▄▀░░░▐░░░░░█▄▀░▐░░░░░
░░█░░░▐░░░░░░░░▄░█░░░░░
░░░█▄░░▀▄░░░░▄▀▐░█░░░░░
░░░█▐▀▀▀░▀▀▀▀░░▐░█░░░░░
░░▐█▐▄░░▀░░░░░░▐░█▄▄░░░
░░░▀▀░▄NOOB ░▐▄▄▄▀░░░░
░░░░░░░░░░░░░░░░░░░░░░░


┻┳|
┳┻| _
┻┳| •.•) Daddy,Are The Spammers Gone?
┳┻|⊂ﾉ
┻┳|
/﹋\
(҂`_´) -NOPE,SON GET BACK IN YOUR BEDROOM
<,︻╦╤─ ҉
/﹋\


░░░░░░░░░░░░░██
░░░░░░░░░░░░█░░█
░░░░░░░░░░░░█░░█
░░░░░░░░░░░█░░░█
░░░░░░░░░░█░░░░█
████████▄▄█░░░░░███████████▄
▓▓▓▓▓▓▓█░░░░░░░░░░░░░░░░░░░█
▓▓▓▓▓▓▓█░░█░░░█▀█░█▀▀░█▀█░░░█
▓▓▓▓▓▓▓█▀▀█▀▀░█▀▄░█▀░░█▀▀░░░█
▓▓▓▓▓▓▓█░░█░░░▀░▀░▀▀▀░▀░░░░█
▓▓▓▓▓▓▓█░░░░░░░░░░░░░░░░░░█
▓▓▓▓▓▓▓█████░░░░░░░░░░░░░█
███████▀░░░░▀▀██████████


...................„-~~'''''''~~--„„_
..............„-~''-,::::::::::::::::::: ''-„
..........,~''::::::::',:::::::::::::::: ::::|',
.....::::::,-~'''¯¯¯''''~~--~'''¯'''-,:|
.........'|:::::|: : : : : : : : : : : ::: : |,'
........|:::::|: : :-~~---: : : -----: |
.......(¯''~-': : : :'¯°: ',: :|: :°-: :|
.....'....''~-,|: : : : : : ~---': : : :,'
...............|,: : : : : :-~~--: : ::/ NEVER GONNA GIVE YOU UP
......,-''\':\: :'~„„_: : : : : _,-' NEVER GONNA LET YOU DOOOWN
__„-';;;;;\:''-,: : : :'~---~''/| NEVER GONNA RUN AROUND AND DESERT YOU
;;;;;/;;;;;;;\: :\: : :____/: :',__
;;;;;;;;;;;;;;',. .''-,:|:::::::|. . |;;;;''-„__
;;;;;;,;;;;;;;;;\. . .''|::::::::|. .,';;;;;;;;;;''-„
;;;;;;;|;;;;;;;;;;;\. . .\:::::,'. ./|;;;;;;;;;;;;;|
;;;;;;;\;;;;;;;;;;;',: : :|¯¯|. . .|;;;;;;;;;,';;|
;;;;;;;;;',;;;;;;;;;;;\. . |:::|. . .'',;;;;;;;;|;;/
;;;;;;;;;;\;;;;;;;;;;;\. .|:::|. . . |;;;;;;;;|/
;;;;;;;;;;;;,;;;;;;;;;;|. .\:/. . . .|;;;;;;;;|

░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░██████╗░███████╗██████╗░░
░░██╗░░██╔══██╗██╔════╝██╔══██╗░
██████╗██████╔╝█████╗░░██████╔╝░ nice on mic and a good igl:steamhappy:
╚═██╔═╝██╔══██╗██╔══╝░░██╔═══╝░░
░░╚═╝░░██║░░██║███████╗██║░░░░░░
░░░░░░░╚═╝░░╚═╝╚══════╝╚═╝░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░

......................,,-~*~,, +Rep
......................./:.:.:.:.:.| +Rep
......................|;.;.;.;.;./ +Rep
......................|.;.;.;.;.| +Rep
............._,,,,,_.).;.;.;.;.| +Rep
.........,,-":.:.:.:."~-,;.;.;.| +Rep
........(_,,,,---,,_:.:.);.;.;..",, +Rep
......,-":.:.:.:.:.""-,,/;.;.;.;.;.", +Rep
.....(:.__,,,,,,,,,___);.;.;.;.;.;| +Rep
...../"":.:.:.:.:.:.:¯""\;.;.;.;.;.," +Rep
....\",__,,,,,,,,,,,__/;;;;;;;;;/\ +Rep
.....\.::.:.:.:.:.:.:.;.);;;;;;;;;/:\ +Rep
.......\,,,,,---~~~~;;;;;;;;,"::::\ +Rep
.........."""~~--,,,,,,,,,,-"::::::::::\ +Rep
...................\:::::::::::::::::::::::\+Rep
░░░░░░░░░░░░░░░░░░+Rep
░█▀▀ ░█▀█ ░█ ░█▀▀ ░░░░+Rep
░█▀▀ ░█▀▀ ░█ ░█ ░░░░░░░+Rep
░▀▀▀ ░▀ ░░░▀ ░▀▀▀ ░░░░░░+Rep
░░░░░░░░░░░░░░░░░░░░░░░ +Rep

LOL found a good Glyph on the web... kinda intresting no Offence tho...
Follow these Steps

1051541451431641621571721571511441234567881234567812345678123678326470547
2999999259923478990124999995689902993413269916749953349999914649932724997
2994567809912568990139956799809929936781467998299634699818991169966144990
2999994569970124995699801323459999012615302799995324993243699019923412993
2994567801993569980299356780239999456725634569974326992644399243992369936
2994567801992689901239967899029939945745315319931253399436998011992349950
2998012345299999388352999991039953991232012479934673289999982640499999415

Step1: Highlight the numbers
Step2: Ctrl and F
Step3: Put 9 in
Step4: Suprise

───▐▀▄──────▄▀▌───▄▄▄▄▄▄▄
───▌▒▒▀▄▄▄▄▀▒▒▐▄▀▀▒██▒██▒▀▀▄
──▐▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▀▄
──▌▒▒▒▒▒▒▒▒▒▒▒▒▒▄▒▒▒▒▒▒▒▒▒▒▒▒▒▀▄
▀█▒▒█▌▒▒█▒▒▐█▒▒▀▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▌
▀▌▒▒▒▒▒▀▒▀▒▒▒▒▒▀▀▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▐ ▄▄
▐▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▄█▒█
▐▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒█▀
──▐▄▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▄▌
────▀▄▄▀▀▀▀▄▄▀▀▀▀▀▀▄▄▀▀▀▀▀▀▄▄▀


░░░░░░░█▐▓▓░████▄▄▄█▀▄▓▓▓▌█
░░░░░▄█▌▀▄▓▓▄▄▄▄▀▀▀▄▓▓▓▓▓▌█
░░░▄█▀▀▄▓█▓▓▓▓▓▓▓▓▓▓▓▓▀░▓▌█
░░█▀▄▓▓▓███▓▓▓███▓▓▓▄░░▄▓▐█▌
░█▌▓▓▓▀▀▓▓▓▓███▓▓▓▓▓▓▓▄▀▓▓▐█
▐█▐██▐░▄▓▓▓▓▓▀▄░▀▓▓▓▓▓▓▓▓▓▌█▌
█▌███▓▓▓▓▓▓▓▓▐░░▄▓▓███▓▓▓▄▀▐█
█▐█▓▀░░▀▓▓▓▓▓▓▓▓▓██████▓▓▓▓▐█
▌▓▄▌▀░▀░▐▀█▄▓▓██████████▓▓▓▌█▌
▌▓▓▓▄▄▀▀▓▓▓▀▓▓▓▓▓▓▓▓█▓█▓█▓▓▌█▌
█▐▓▓▓▓▓▓▄▄▄▓▓▓▓▓▓█▓█▓█▓█▓▓▓▐█

⡴⠑⡄⠀⠀⠀⠀⠀⠀⠀ ⣀⣀⣤⣤⣤⣀⡀
⠸⡇⠀⠿⡀⠀⠀⠀⣀⡴⢿⣿⣿⣿⣿⣿⣿⣿⣷⣦⡀
⠀⠀⠀⠀⠑⢄⣠⠾⠁⣀⣄⡈⠙⣿⣿⣿⣿⣿⣿⣿⣿⣆
⠀⠀⠀⠀⢀⡀⠁⠀⠀⠈⠙⠛⠂⠈⣿⣿⣿⣿⣿⠿⡿⢿⣆
⠀⠀⠀⢀⡾⣁⣀⠀⠴⠂⠙⣗⡀⠀⢻⣿⣿⠭⢤⣴⣦⣤⣹⠀⠀⠀⢀⢴⣶⣆
⠀⠀⢀⣾⣿⣿⣿⣷⣮⣽⣾⣿⣥⣴⣿⣿⡿⢂⠔⢚⡿⢿⣿⣦⣴⣾⠸⣼⡿
⠀⢀⡞⠁⠙⠻⠿⠟⠉⠀⠛⢹⣿⣿⣿⣿⣿⣌⢤⣼⣿⣾⣿⡟⠉
⠀⣾⣷⣶⠇⠀⠀⣤⣄⣀⡀⠈⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇
⠀⠉⠈⠉⠀⠀⢦⡈⢻⣿⣿⣿⣶⣶⣶⣶⣤⣽⡹⣿⣿⣿⣿⡇
⠀⠀⠀⠀⠀⠀⠀⠉⠲⣽⡻⢿⣿⣿⣿⣿⣿⣿⣷⣜⣿⣿⣿⡇
⠀⠀ ⠀⠀⠀⠀⠀⢸⣿⣿⣷⣶⣮⣭⣽⣿⣿⣿⣿⣿⣿⣿⠇
⠀⠀⠀⠀⠀⠀⣀⣀⣈⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠇
⠀⠀⠀⠀⠀⠀⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿

⢸⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⡷⠀⠀
⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠢⣀⠀⠀
⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇ Are you winning son?
⢸⠀⠀⠀⠀ ⠖⠒⠒⠒⢤⠀⠀⠀⠀⠀⡇⠀⠀
⢸⠀⠀⣀⢤⣼⣀⡠⠤⠤⠼⠤⡄⠀⠀⡇⠀
⢸⠀⠀⠑⡤⠤⡒⠒⠒⡊⠙⡏⠀⢀⠀⡇⠀
⢸⠀⠀⠀⠇⠀⣀⣀⣀⣀⢀⠧⠟⠁⠀⡇
⢸⠀⠀⠀⠸⣀⠀⠀⠈⢉⠟⠓⠀⠀⠀⠀
⢸⠀⠀⠀⠀⠈⢱⡖⠋⠁⠀⠀⠀⠀⠀⠀⡇
⢸⠀⠀⠀⠀⣠⢺⠧⢄⣀⠀⠀⣀⣀⠀⠀⡇
⢸⠀⠀⠀⣠⠃⢸⠀⠀⠈⠉⡽⠿⠯⡆
⢸⠀⠀⣰⠁⠀⢸⠀⠀⠀⠀⠉⠉⠉⠀⠀⡇
⢸⠀⠀⠣⠀⠀⢸⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀
⢸⠀⠀⠀⠀⠀⢸⠀⢇⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀

rose 
⠿⠛⠉⠀⠒⠻⢿⣿⣿⣿⣇⡀
⠀⣠⣶⣾⡏⢁⣴⣾⣿⣿⣿⣶⣦⡈⢻⣿⣿⣷
⢰⣿⣿⣿⠀⢼⠿⠛⠉⠉⠉⠙⠻⣿⠀⢻⣿⠿⢀⣤⣶⣦⣄⡀
⢸⣿⡟⠉⣀⣠⠆⢀⣴⣶⣦⣄⠀⠙⠀⠸⣿⣦⣈⠻⠿⠛⠉⠁
⠈⢿⡀⢰⣿⡟⠀⢾⣿⡿⠋⣁⣤⣾⡇⠀⣿⣿⣿⣦
⢸⡌⠃⠸⣿⡁⠀⠘⠟⢁⣾⣿⣿⣿⡇⠀⣿⣿⣿⡿
⠈⣿⣦⣀⠉⠃⠀⣠⣶⣿⣿⡿⠿⠛⢁⣼⣿⡿⠋⠠⠤⢶⣤⡀
⠀⢸⣿⣿⣿⣦⣄⣈⣉⣩⣤⣄⡀⠺⠿⠿⠛⣁⣴⣶⣶⣦⣹⣿⡄
⠀⠈⠻⢿⣿⣿⣿⣿⣿⣿⡿⠟⠉⠸⡄⠀⠀⠀⠈⠉⠙⠻⣿⣿⡇
⠀⠀⠀⠀⠀⠉⠉⠉⢉⠁⣠⣴⣷⠀⠘⡄⠀⠀⠀⠀⠀⠀⠈⠿⠁
⠀⠀⠀⠀⠀⠀⢀⣾⣇⣼⣿⣿⡿⠀⠀⢠
⠀⠀⠀⠀⠀⠀⢸⣿⣿⠿⠟⠋⠀⠀⠀⢸
⠀⠀⠀⠀⠀⠀⠘⠋⠀⠀⠀⠀⠀⠀⠀⢸
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡌
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠚⠁

cat 
..........................／＞　　フ <3
.........................| 　_　 _ l
......................／` ミ＿x＿ノ Have a nice week
..................../　　　　 |
................../　 ヽ　　 ﾉ
.................│　　|　|　|
..........／￣|　　 |　|　|
..........| (￣ヽ＿_ヽ_)__)
..........＼二つ

 :sd::sd::sd::sd::sd::sd:  :sd::sd::sd::sd::sd::sd::sd:  
  :sd::sd::sd::sd::sd::sd:  :sd::sd::sd::sd::sd::sd::sd:  
  :sd::sd:                    :sd::sd:  
  :sd::sd:                  :sd::sd:    
  :sd::sd::sd::sd::sd::sd:        :sd::sd:      
  :sd::sd::sd::sd::sd::sd:      :sd::sd:        
  :sd::sd:            :sd::sd:          
  :sd::sd:          :sd::sd:            
  :sd::sd::sd::sd::sd::sd:  :sd::sd::sd::sd::sd::sd::sd:  
  :sd::sd::sd::sd::sd::sd:  :sd::sd::sd::sd::sd::sd::sd:  

Niko is as cracked as he is jacked. Saw him at 7-11 the other day an he was buying cases of Redbull and adult diapers. I asked him what the diapers were for an he said, “they help contain my full power so I don’t completely sh i t on these kids” and then he bunny hopped out the door

https://steamcommunity.com/profiles/76561198290950776 >> same talon knife

youtube com/watch?v=22mv251bt_U >> AroraJi Stream


Card Flip joker artwork guide steal lmao >> https://steamcommunity.com/sharedfiles/filedetails/?id=1086064463

MM Failed to Accept PopUp Glitch https://steamcommunity.com/app/730/discussions/0/1640918469758063466/

http://steamcommunity.com/profiles/76561199115290348 >> Profile description
I wont let the inner child in me die, bachpana toh rahega mujmhe hamesha, age chahe kitni bi badi hojaaye kyunki "Growing up comes at the cost of innocence of child" sorry boss innocence, imaandari, masti, mazaak, khel khud ye mujhme khatam nahi honewala.
