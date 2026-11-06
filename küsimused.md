1. Milliseid erinevaid viise leidub teksti kaheks jaotamiseks?
   1) CSS Grid
      .konteiner {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 16px;
      }
   2) Flexbox
      .konteiner {
              display: flex;
              gap: 16px;
            }
            
      .tulp {
              flex: 1;
            }
    3) CSS Columns
       .tekst {
          columns: 2;
          column-gap: 24px;
        }
3. Miks on inline CSS halb?
   Sest see on kole ja segane ja ebaefektiivne.
