# Ruby Guild 5/4/2017

learn Active Records

#retrieve object
bisa mencari berdasarkan id, atribut
find_by maksimal untuk positive match, selain itu tidak bisa.
find : error bila tidak ada
find_by : bila tidak ada return Nil object

.first #return active record
.first(x) #return array, beda penanganan

#condition
.where #bisa negative match

#ordering

#join : memudahkan sekali, misalpun kita belum terlalu paham konsep join di sql (querynya)

#includes


#kegunaan
- memudahkan kita query dengan minimum query
- 

resource : 
http://slides.com/qblfrb/active-record
https://en.wikipedia.org/wiki/Active_record_pattern
http://guides.rubyonrails.org/active_record_basics.html