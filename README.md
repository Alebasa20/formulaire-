<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>registre</title>
</head>
<body>
    <form>
        <fieldset>
            <legend>Vos coordonnees</legend>
        <table>
                <tr>
                    <td>
                        Name :
                    </td>
                    <td>
                        <input type="text" placeholder="votre nom" name="nom" id="nom" required>
                    </td>
                </tr>
                <tr>
                    <td>
                       Prenom :
                    </td>
                    <td>
                        <input type="text" placeholder="votre prenom" name="prenom" id="prenom" required>
                    </td>
                </tr>
                <tr>
                    <td>
                        Date de naissance :
                    </td>
                    <td>
                        <input type="date" name=" date" id="date" min="1900-01-01" required>
                    </td>
                </tr>
                <tr>
                    <td>
                        Mail :
                    </td>
                    <td>
                        <input type="email" placeholder="votre mail" name="email" id="email">
                    </td>
                </tr>
                <tr>
                    <td>
                        votre site :
                    </td>
                    <td>
                        <input type="text" name="site" id="site">
                    </td>
                </tr>
                <tr>
                    <td>
                        Code :
                    </td>
                    <td>
                        <input type="password" name="password" required>
                    </td>
                </tr>
                <tr>
                    <td>
                        Genre :
                    </td>
                    <td>
                        <input type="radio" name="genre">homme
                        <br/>
                        <input type="radio" name="genre">Femme
                    </td>
                </tr>
                <tr>
                    <td>
                        Pays :
                    </td>
                    <td>
                        <select name="pays" id="pays" placeholder="votre pays">
                            <option value="Algerie">Algerie</option>
                            <option value="allemagne">Allemagne</option>
                            <option value="benin">Benin</option>
                            <option value="bresil">Bresil</option>
                            <option value="cameroun">Cameroun</option>
                            <option value="ghana">Ghana</option>
                            <option value="etats-unis">Etats-unis</option>
                            <option value="france">France</option>
                            <option value="grande bretagne">Grande bretagne</option>
                            <option value="togo">Togo</option>
                            <option value="chine">Chine</option>
                            <option value="espagne">Espagne</option>
                            <option value="japon">Japon</option>
                            <option value="isreal">Isreal</option>
                        </select>
                    </td>
                </tr>
        </table>
        </fieldset>
        <fieldset>
            <legend>Vos goûts</legend>
            <input type="checkbox" name="tare aux fraises à la crème d'amandes" id="tarte aux fraises à la crème d'amandes" />
      <label for="tare aux fraises à la crème d'amandes">Tare aux fraises à la crème d'amandes</label><br/>
            <input type="checkbox" name="tarte aux prunes" id="tarte aux prunes" /><label for="tarte aux prunes">Tarte aux prunes</label><br/>
            <input type="checkbox" name="tarte rustique aux mirabelles de lorraine,noisettes et miel" id="tarte rustique aux mirabelles de lorraine,noisettes et miel" />
      <label for="tarte rustique aux mirabelles de lorraine,noisettes et miel">Tarte rustique aux mirabelles de lorraine,noisettes et miel</label><br/>
            <textarea name="décrivez" id="décrivez" rows="5" cols="50">
Décrivez vos goûts en détail
            </textarea>
       </fieldset>
       <fieldset>
           <legend>Envoyez nous votre photo</legend>
           <input type="file" value="Envoyer une photo" />
           <br/><br/>
           <button type="reset">Effacer</button>
           <button type="submit">Envoyer</button>
       </fieldset>
    </form>
</body>
</html>
