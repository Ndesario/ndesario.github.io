<!DOCTYPE html>

<html>
    <head>
        <title>farming form</title>
    </head>
    <style>
                body {
                    font-family: 'Times New Roman', Times, serif;
                    font-size: 1.5em;
                    line-height: 1.5;
                    text-align: justify;
                    background-image:url(watermellon.jpg)
                }
            fieldset {
                    background-color:lightgreen;
                    background-size: 40cm;
                    background-position: left;
                }
                
                body h2,h3 {
                    text-decoration: solid;
                    color:wheat;
                    text-align: center;
                    font-family:'Times New Roman';
                    font-size:1cm;
                    margin-bottom: 0%;
                    margin-top: 0%;
                    margin-left: 0%;
                    margin-right: 0%;
                
                }
                radio {
                    font-style: normal;
                    font-weight: bold;
                    color: lightgreen;
                }
            
                textarea {
                      background-color: lightgreen; 
                      margin-top: 1%; 
                      margin-left: 1%;       
                }
                input {
                    background-color: lightgreen;
                }
                h4 {
                    text-align: right;
                    margin-bottom: 0%;
                    color: maroon;
                }
            form {
                    background-image: url(watermellon.jpg);
                }
                footer{
                    text-align: center;
                    font-weight: lighter;
                    font-style: italic;
                }
                p {
                    color: rgb(114, 114, 125);
                    font-style: italic;
                }
            </style>
    <body>
        <fieldset>  
            <form method="POST">
                <h2>
                    <img src="watermellon.jpg" width="100">
                        KILIMO CHA TIKITI
                    <img src="watermellon.jpg" width="100">
                </h2>
            <h3>MASWALI KUHUSU KILIMO</h3>
            <h4>UTAFITI</h4>
        </fieldset>   
            <hr>
        <fieldset>
        <ol>
            <li>Katika masoko bei ya kuuza tikiti lenye ubora</li>
                <label>Minimum:</label><input type="text">
                <label>Maximum:</label><input type="text">
            <li>Upi ni msimu bora wa kupanda matikiti, ukizingatia mabadiliko ya tabia ya nchi?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Wakati wa uvunaji wa tikiti zilizo shambani, zinahitaji kuvunwa kwa awamu ngapi?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Uhifadhi bora wa tikiti zilizovunwa ni upi, na unahusianaje na kikonyo chake, na muda gani?</li>
                 <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Kutoka Kangeta kilimo, tunaweza kupata mahitaji yafuatayo kwa ardhi ekari moja?
            <div>
                Mbegu,Mbolea,Dawa,Mitego ya wadudu,Dripping
            </div>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            </li>
            <li>Je ni namna gani ya kuweka uhusiano mzuri baina ya vifuatavyo; 
                <br>-kipindi cha kutoa maua 
                <br>-nyuki 
                <br>-dawa za wadudu
            </li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Je, busta zote ni muhimu kupiga? kipindi cha mimea michanga, maua, matunda?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Kipindi gani cha ukuaji wa tikiti kina changamoto nyingi zaidi na kinahitaji uangalizi wa karibu zaidi?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Baada ya kujua historia ya shamba, je unaweza kurudia kupanda tikiti katika ardhi ambayo tikiti limeshapandwa msimu wa nyuma? </li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Ni mbolea ipi ungependekeza zaidi kutumika wakati wa kupanda kwa matokeo bora zaidi?</li>
        <div>
            <input type="radio" name="mbolea">Samadi
            <input type="radio" name="mbolea">DAP
                <textarea name="jibu" id="text" cols="50" rows="3">Maelezo ya ziada:</textarea>
        </div>
            <li>Nafasi kutoka mmea mmoja kwenda mmea mwingine,shina moja kwenda shina jingine, ni kiasi gani bora zaidi?</li>
                <textarea name="jibu" id="text" cols="100" rows="5"></textarea>
            <li>Aina gani ya mbegu ni bora, huleta matunda makubwa na matamu?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Je kwa herari moja inaweza hitaji wafanyakazi wangapi, na malipo yao kwa makadirio inaweza kuwa kiasi gani?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
            <li>Je unafahamu shamba au sehemu wanakodisha mashamba kwa bei nzuri na kuna chanzo cha maji?</li>
                <textarea name="jibu" id="text" cols="100" rows="5">Jibu:</textarea>
        </ol>
            <p>
                Bonyeza hapa kuwasilisha >>> <input type="SUBMIT" name="SUBMIT">
            </p>
            <footer>
                Asante kwa ushirikiano wako, na Mungu akubariki sana. <br>
                &copy; 2023 Watermellon Project (Carl vs Rio)
            </footer>
        </form>
    </fieldset>
    </body>
</html>
