
- **BSON** (Binary JSON) este un format de serializare binară derivat din [[JSON]], utilizat de [[MongoDB]] pentru a stoca documente.
- Spre deosebire de JSON, BSON include tipuri suplimentare (ex: `Date`, `int`, `long`, `decimal128`) și este optimizat pentru viteză la parsare.
- Suportă indexare eficientă și permite căutări rapide în bazele de date document-oriented.
- Fiind binar, este mai compact și performant pentru stocare și rețea, dar nu este ușor de citit de către oameni.
- BSON este folosit intern de MongoDB, dar poate fi utilizat și în aplicații care cer eficiență la transferul de date binare.

