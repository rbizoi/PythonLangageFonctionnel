<table>
<tr>                                                                                   
     <th>
         <div>Formation Python </div>
     </th>
 </tr>
<tr>                                                                                   
     <th><img src="https://raw.githubusercontent.com/rbizoi/PythonLangageFonctionnel/refs/heads/master/images/python-image-logo-940x530.jpeg" width="1024"></th>
 </tr>    
</table>

<b><div>Installation</div></b>

<table>
    <tr>                                                                                   
         <th><a href="https://www.anaconda.com/download/success">
               <img src="https://raw.githubusercontent.com/rbizoi/PythonLangageFonctionnel/refs/heads/master/images/anaconda.png" width="512">
             </a>
         </th>
    </tr>    
</table>

<br>
<b></b><a href="https://www.anaconda.com/download/success">Installation Anaconda</a></b>
<br>
<div>Mise à jour des librairies de l’environnement <b>base</b></div>

```
conda activate root
conda update --all
python -m pip install --upgrade pip
```

<div>Création de l’environnement <b>cours</b> </div>
<br>
<div><b>Windows</b> </div>
<br>

```
# conda remove -n cours --all -y
conda create -n cours -c conda-forge  python==3.10 ipython ipython-sql jupyter notebook numpy pandas pyarrow matplotlib seaborn colour pydot pyyaml scikit-image scikit-learn plotly

conda activate cours
```

<br>
<div><b>Linux</b> </div>
<br>

```
# conda remove -n cours --all -y
conda create -p /home/utilisateur/anaconda3/envs/cours -c conda-forge  python==3.10 ipython ipython-sql jupyter notebook numpy pandas pyarrow matplotlib seaborn colour pydot pyyaml scikit-image scikit-learn plotly

conda activate cours
```


