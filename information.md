# Temp_box
WEEK1-LAB001

ข้อมูลการออกแบบของส่วนประกอบแต่หละชิ้น







information design {
        FRAME มีทั้งหมด 5 body {
                              Frame1 < จะเป็นกรอบในส่วนของฝากล่อง > < โดยฝากล่องจะมี 2 ขอบที่ซ้อนกันอยู่ >
                                   { < ขนาดของกรอบรอบนอกสุด>
                                       Width : 57mm
                                       Length : 90mm
                                       Height : 7mm
                                   }
                                   { < ขนาดของกรอบด้านในชั้นที่ 2>
                                       Width : 55mm
                                       Length : 88mm
                                       Height : 7mm
                                   }

                              FRAMEtop < จะเป็นแผ่นของฝากล่องที่เราเอามาซ้อนบน frame1 อีกที> {
                                   Frame2 {
                                        Pad006 {
                                                      { < กรอบด้านนอกสุด >
                                                           Width : 57mm
                                                           Length : 90mm
                                                           Height : 1mm
                                                      }

                                                      { < เจาะเป็นสี่เหลี่ยมไว้สำหรับวาง switch และ dht22 >
                                                            { < switch >
                                                                 Width : 12mm
                                                                 Length : 18mm
                                                                 Height : 1mm
                                                           }
                                                           { < dht22 >
                                                                Width : 14mm
                                                                Length : 18mm
                                                                Height : 1mm
                                                            }
 
                                                      { < เจาะรูไว้สำหรับ led >
                                                            Diameter : 3mm
                                                            Height: 1mm
                                                            Length(จากกรอบ) : 3mm
                                                            Height(จากกรอบ) : 3mm
                                                      }

                                                     { < เจาะรูไว้สำหรับน็อต >
                                                          Diameter : 2mm
                                                          Height: 1mm
                                                          Length(เส้นกลาง) : 20mm
                                                          Height(จากกรอบ) : 15mm
                                                     }
                                                     }


                                        Pad007 {
                                                      { < กรอบด้านนอกสุด >
                                                           Width : 55mm
                                                           Length : 88mm
                                                           Height : 1mm
                                                      }

                                                      { < เจาะเป็นสี่เหลี่ยมไว้สำหรับวาง switch และ dht22 >
                                                            { < switch >
                                                                 Width : 12mm
                                                                 Length : 18mm
                                                                 Height : 1mm
                                                           }
                                                           { < dht22 >
                                                                Width : 14mm
                                                                Length : 18mm
                                                                Height : 1mm
                                                            }
 
                                                      { < เจาะรูไว้สำหรับ led >
                                                            Diameter : 3mm
                                                            Height: 1mm
                                                            Length(จากกรอบ) : 20mm
                                                            Height(จากกรอบ) : 14mm
                                                      }

                                                     { < เจาะรูไว้สำหรับน็อต >
                                                          Diameter : 2mm
                                                          Height: 1mm
                                                          Length(จากกรอบ) : 2mm
                                                          Height(จากกรอบ) : 2mm
                                                     }
                                                     }


                             radius1 < เจาะรูและกรอบสำหรับใส่น็อต > < ขวาล่าง >
                                   {  < รูน็อต >
                                       Width : 5mm
                                       Length : 5mm
                                       Height : 8mm
                                       Length(เส้นกลาง) : 44mm
                                       Height(เส้นกลาง) : 125.5mm
                                   }
                                 
                                  {  < กรอบของรูน็อต >
                                       Diameter : 10mm
                                       Length : 2mm
                                       Height : 8mm
                                   }


                             radius2 < เจาะรูและกรอบสำหรับใส่น็อต > < ซ้ายล่าง >
                                   {  < รูน็อต >
                                       Width : 5mm
                                       Length : 5mm
                                       Height : 8mm
                                       Length(เส้นกลาง) : 44mm
                                       Height(เส้นกลาง) : 125.5mm
                                   }
                                 
                                  {  < กรอบของรูน็อต >
                                       Diameter : 10mm
                                       Length : 2mm
                                       Height : 2mm
                                   }


                             radius3 < เจาะรูและกรอบสำหรับใส่น็อต > < ขวาล่าง >
                                   {  < รูน็อต >
                                       Width : 5mm
                                       Length : 5mm
                                       Height : 8mm
                                       Length(เส้นกลาง) : 44mm
                                       Height(เส้นกลาง) : 74.5mm
                                   }
                                 
                                  {  < กรอบของรูน็อต >
                                       Diameter : 10mm
                                       Length : 2mm
                                       Height : 2mm
                                   }


                             radius4 < เจาะรูและกรอบสำหรับใส่น็อต > < ขวาล่าง >
                                   {  < รูน็อต >
                                       Width : 5mm
                                       Length : 5mm
                                       Height : 8mm
                                       Length(เส้นกลาง) : 44mm
                                       Height(เส้นกลาง) : 74.5mm
                                   }
                                 
                                  {  < กรอบของรูน็อต >
                                       Diameter : 10mm
                                       Length : 2mm
                                       Height : 2mm
                                   }


########################################################################################################################################################

       BODY มีทั้งหมด 2 body {
                             Body < เป็นแผ่นรองกล่องข้างล่างสุด > {
                                   Pad {
                                          { < ขนาดของแผ่นรองกล่อง >
                                                Radius : 6mm
                                                Width : 57mm
                                                Length : 78mm
                                                Height : 2mm
                                          }

                                          { < รูเจาะ 4 จุดรอบนอก >
                                               Radius : 1.28mm
                                               Width : 55mm
                                               Height : 2mm
                                               Length(จากกรอบ) : 17mm
                                               Height(จากกรอบ) : 3mm
                                          }

                                          { < เจาะเป็นแผ่นสี่เหลี่ยม >
                                               Width : 35mm
                                               Length: 49mm
                                               Height : 2mm
                                          }
      
                                          { < รูน็อต 3 รูไว้ยึด delay>
                                               Diameter : 2mm
                                               Height : 2mm
                                          }



                                   Pad009 < เป็นแผ่นรองกล่องข้างล่างสุด >
                                          { < ขนาดของแผ่นรองกล่อง >
                                               Radius : 6mm
                                               Width : 57mm
                                               Length : 78mm
                                               Height : 15mm
                                          }

                                          { < รูเจาะ 4 จุดรอบนอก >
                                               Radius : 1.28mm
                                               Width : 55mm
                                               Height : 15mm
                                               Length(จากกรอบ) : 17mm
                                               Height(จากกรอบ) : 3mm
                                          }

                                          { < เจาะเป็นแผ่นสี่เหลี่ยม >
                                               Width : 35mm
                                               Length: 49mm
                                               Height : 15mm
                                          }

                                          { < รูน็อต 3 รูไว้ยึด delay>
                                               Diameter : 2mm
                                               Height : 15mm
                                          }


                                          { < เจาะรูและกรอบสำหรับใส่น็อต > < ขวาล่าง >
                                            < รูน็อต >
                                                Width : 5mm
                                                Length : 5mm
                                                Height : 8mm
                                                Length(เส้นกลาง) : 44mm
                                                Height(เส้นกลาง) : 125.5mm
                                 
                                            < กรอบของรูน็อต >
                                               Diameter : 10mm
                                               Length : 2mm
                                               Height : 8mm
                                           }


                                          { < เจาะรูและกรอบสำหรับใส่น็อต > < ซ้ายล่าง >
                                            < รูน็อต >
                                               Width : 5mm
                                               Length : 5mm
                                               Height : 8mm
                                               Length(เส้นกลาง) : 44mm
                                               Height(เส้นกลาง) : 125.5mm                               
                                 
                                            < กรอบของรูน็อต >
                                               Diameter : 10mm
                                               Length : 2mm
                                               Height : 2mm
                                          }


                                          { < เจาะรูและกรอบสำหรับใส่น็อต > < ขวาล่าง >
                                            < รูน็อต >
                                               Width : 5mm
                                               Length : 5mm
                                               Height : 8mm
                                               Length(เส้นกลาง) : 44mm
                                               Height(เส้นกลาง) : 74.5mm

                                            < กรอบของรูน็อต >
                                               Diameter : 10mm
                                               Length : 2mm
                                               Height : 2mm
                                          }


                                          { < เจาะรูและกรอบสำหรับใส่น็อต > < ขวาล่าง >
                                            < รูน็อต >
                                              Width : 5mm
                                              Length : 5mm
                                              Height : 8mm
                                              Length(เส้นกลาง) : 44mm
                                              Height(เส้นกลาง) : 74.5mm

                                           < กรอบของรูน็อต >
                                              Diameter : 10mm
                                              Length : 2mm
                                              Height : 2mm
                                          }



                             ahother < แผ่นที่วางไว้ตรงช่องสี่เหลี่ยมที่เจาะสำหรับวาง Breadboard > {
                                   Pad010 {
                                          { < ขนาดของแผ่นรองกล่อง >
                                                Width : 35mm
                                                Length : 49mm
                                                Height : 1mm
                                          }





########################################################################################################################################################
        BOX มีทั้งหมด 6 body {
                            box1 < จะเป็นกรอบของ box ด้านในที่เราร่างเอาไว้เป็นขอบ (ขอบล่าง) > {
                                   { < ขนาดของกรอบรอบนอกสุด >
                                       Width : 57mm
                                       Length : 90mm
                                       Height : 2mm
                                   }
                                   { < ขนาดของกรอบด้านในชั้นที่ 2 >
                                       Width : 55mm
                                       Length : 88mm
                                       Height : 7mm
                                   }

                            inside < จะเป็นกรอบของ box ด้านในที่เราร่างเอาไว้เป็นขอบ (ขอบบน) > {
                                   { < ขนาดของกรอบรอบนอกสุด >
                                       Width : 57mm
                                       Length : 90mm
                                       Height : 3mm
                                   }
                                   { < ขนาดของกรอบด้านในชั้นที่ 2 >
                                       Width : 55mm
                                       Length : 88mm
                                       Height : 3mm
                                   }


                            box2 < เป็นส่วนของขอบด้านข้างแนวยาวฝั่งขวา > {
                                   { < ขนาด >
                                       Width : 1mm
                                       Length : 90mm
                                       Height : 12mm
                                   }


                            box3 < เป็นส่วนของขอบด้านข้างแนวยาวฝั่งซ้าย > {
                                   { < ขนาด >
                                       Width : 1mm
                                       Length : 90mm
                                       Height : 12mm
                                   }

                            box4 <  เป็นส่วนของขอบด้านข้างแนวกว้างฝั่งขวา > {
                                   { < ขนาด >
                                       Width : 1mm
                                       Length : 57mm
                                       Height : 12mm
                                   }

                                  { < เจาะเป็นช่องสี่เหลี่ยมไว้สำหรับ USB >
                                       Width : 1mm
                                       Length : 13mm
                                       Height : 7mm
                                   }

                                  { < เจาะเป็นวงกลมไว้สำหรับจ่ายไฟ >
                                       Diameter : 7mm
                                       Width : 1mm
                                       Length : 13mm
                                       Width(จากเส้นกลาง) :  12.5mm
                                       Height(จากพื้น) : 8mm
                                   }

                            box4 <  เป็นส่วนของขอบด้านข้างแนวกว้างฝั่งซ้าย > {
                                   { 
                                       Width : 1mm
                                       Length : 57mm
                                       Height : 12mm
                                   }



 

