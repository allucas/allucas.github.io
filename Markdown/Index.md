    <IPython.core.display.Javascript object>


# COVID-19 Vaccine Development Tracker

Welcome to **covid-vaccine-tracker.com**. This website presents a summary of the data published by the WHO regarding the develipment of COVID-19 vaccines (https://www.who.int/blueprint/priority-diseases/key-action/novel-coronavirus-landscape-ncov.pdf?ua=1). No modifications have been made to the data, and it has been done as an attempt to make this information more easily accessible to the public. The website is updated on a daily basis.

### COVID-19 Vaccine Platforms in Development

    Got stderr: Mar 27, 2020 3:40:28 PM org.apache.pdfbox.pdmodel.font.PDCIDFontType2 <init>
    INFO: OpenType Layout tables used in font BCDGEE+Calibri-Light are not implemented in PDFBox and will be ignored
    Mar 27, 2020 3:40:29 PM org.apache.pdfbox.pdmodel.font.PDCIDFontType2 <init>
    INFO: OpenType Layout tables used in font BCDIEE+Calibri are not implemented in PDFBox and will be ignored
    


    findfont: Font family ['normal'] not found. Falling back to DejaVu Sans.
    findfont: Font family ['normal'] not found. Falling back to DejaVu Sans.



![png](Index_files/Index_5_1.png)


<pre>






</pre>



### Clincal Trial Phase


![png](Index_files/Index_7_0.png)


# Data

I have filtered the WHO data and made it more accessible. If you would like a spreadsheet version of this data, please email me at: *covid.vaccine.tracker@gmail.com*




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Vaccine Platform</th>
      <th>Vaccine Specifics</th>
      <th>Company/Developer</th>
      <th>Trial Stage</th>
      <th>Other Uses</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Non- Replicating Viral Vector</td>
      <td>Adenovirus Type 5 Vector</td>
      <td>CanSino Biological Inc. and Beijing Institute ...</td>
      <td>Phase 1</td>
      <td>Ebola</td>
    </tr>
    <tr>
      <th>1</th>
      <td>RNA</td>
      <td>LNP- encapsulated mRNA</td>
      <td>Moderna/NIAID</td>
      <td>Phase 1</td>
      <td>multiple candidates</td>
    </tr>
    <tr>
      <th>5</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>6</th>
      <td>DNA</td>
      <td>DNA plasmid vaccine Electroporation device</td>
      <td>Inovio Pharmaceuticals</td>
      <td>Pre-Clinical</td>
      <td>Lassa, Nipah HIV Filovirus HPV Cancer indicati...</td>
    </tr>
    <tr>
      <th>7</th>
      <td>DNA</td>
      <td>DNA</td>
      <td>Takis/Applied DNA Sciences/Evvivax</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>8</th>
      <td>DNA</td>
      <td>DNA plasmid vaccine</td>
      <td>Zydus Cadila</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Inactivated</td>
      <td>Formaldehyde- inactivated + alum</td>
      <td>Sinovac</td>
      <td>Pre-Clinical</td>
      <td>SARS</td>
    </tr>
    <tr>
      <th>10</th>
      <td>Live Attenuated Virus</td>
      <td>Deoptimized live attanuated vaccines</td>
      <td>Codagenix/Serum Institute of India</td>
      <td>Pre-Clinical</td>
      <td>HAV, InfA, ZIKV, FMD, SIV, RSV, DENV</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Non- Replicating Viral Vector</td>
      <td>MVA encoded VLP</td>
      <td>GeoVax/BravoVax</td>
      <td>Pre-Clinical</td>
      <td>LASV, EBOV, MARV, HIV</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Non- Replicating Viral Vector</td>
      <td>Ad26 (alone or with MVA boost)</td>
      <td>Janssen Pharmaceutical Companies</td>
      <td>Pre-Clinical</td>
      <td>Ebola, HIV, RSV</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Non- Replicating Viral Vector</td>
      <td>ChAdOx1</td>
      <td>University of Oxford</td>
      <td>Pre-Clinical</td>
      <td>influenza, TB, Chikungunya, Zika, MenB, plague</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Non- Replicating Viral Vector</td>
      <td>adenovirus- based NasoVAX expressing SARS2-CoV...</td>
      <td>Altimmune</td>
      <td>Pre-Clinical</td>
      <td>influenza</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Non- Replicating Viral Vector</td>
      <td>Ad5 S (GREVAXTM platform)</td>
      <td>Greffex</td>
      <td>Pre-Clinical</td>
      <td>MERS</td>
    </tr>
    <tr>
      <th>16</th>
      <td>Non- Replicating Viral Vector</td>
      <td>Oral Vaccine platform</td>
      <td>Vaxart</td>
      <td>Pre-Clinical</td>
      <td>InfA, CHIKV, LASV, NORV; EBOV, RVF, HBV, VEE</td>
    </tr>
    <tr>
      <th>17</th>
      <td>Protein Subunit</td>
      <td>Drosophila S2 insect cell expression system VLPs</td>
      <td>ExpreS2ion</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>18</th>
      <td>Protein Subunit</td>
      <td>S protein</td>
      <td>WRAIR/USAMRIID</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>19</th>
      <td>Protein Subunit</td>
      <td>S-Trimer</td>
      <td>Clover Biopharmaceuticals Inc./GSK</td>
      <td>Pre-Clinical</td>
      <td>HIV, REV Influenza</td>
    </tr>
    <tr>
      <th>20</th>
      <td>Protein Subunit</td>
      <td>Peptide</td>
      <td>Vaxil Bio</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>21</th>
      <td>Protein Subunit</td>
      <td>S protein</td>
      <td>AJ Vaccines</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>22</th>
      <td>Protein Subunit</td>
      <td>Ii-Key peptide</td>
      <td>Generex/EpiVax</td>
      <td>Pre-Clinical</td>
      <td>Influenza, HIV, SARS- CoV</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Protein Subunit</td>
      <td>S protein</td>
      <td>EpiVax/Univ. of Georgia</td>
      <td>Pre-Clinical</td>
      <td>H7N9</td>
    </tr>
    <tr>
      <th>24</th>
      <td>Protein Subunit</td>
      <td>S protein (baculovirus production)</td>
      <td>Sanofi Pasteur</td>
      <td>Pre-Clinical</td>
      <td>Influenza, SARS-CoV</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Protein Subunit</td>
      <td>Full length S trimers/ nanoparticle + Matrix M</td>
      <td>Novavax</td>
      <td>Pre-Clinical</td>
      <td>RSV; CCHF, HPV, VZV, EBOV</td>
    </tr>
    <tr>
      <th>26</th>
      <td>Protein Subunit</td>
      <td>gp-96 backbone</td>
      <td>Heat Biologics/Univ. Of Miami</td>
      <td>Pre-Clinical</td>
      <td>NSCLC, HIV, malaria, Zika</td>
    </tr>
    <tr>
      <th>27</th>
      <td>Protein Subunit</td>
      <td>Molecular clamp stabilized Spike protein</td>
      <td>University of Queensland/GSK</td>
      <td>Pre-Clinical</td>
      <td>Nipah, influenza, Ebola, Lassa</td>
    </tr>
    <tr>
      <th>28</th>
      <td>Protein Subunit</td>
      <td>S1 or RBD protein</td>
      <td>Baylor College of Medicine</td>
      <td>Pre-Clinical</td>
      <td>SARS</td>
    </tr>
    <tr>
      <th>29</th>
      <td>Protein Subunit</td>
      <td>Subunit protein, plant produced</td>
      <td>iBio/CC-Pharming</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>30</th>
      <td>Protein Subunit</td>
      <td>Subunit</td>
      <td>VIDO-InterVac, University of Saskatchewan</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>31</th>
      <td>Protein Subunit</td>
      <td>Adjuvanted microsphere peptide</td>
      <td>University of Saskatchewan</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>32</th>
      <td>Replicating Viral Vector</td>
      <td>Measles Vector</td>
      <td>Zydus Cadila</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>33</th>
      <td>Replicating Viral Vector</td>
      <td>Measles Vector</td>
      <td>Institute Pasteur/Themis/Univ. of Pittsburg Ce...</td>
      <td>Pre-Clinical</td>
      <td>West nile, chik, Ebola, Lassa, Zika</td>
    </tr>
    <tr>
      <th>34</th>
      <td>Replicating Viral Vector</td>
      <td>Horsepox vector expressing S protein</td>
      <td>Tonix Pharma/Southern Research</td>
      <td>Pre-Clinical</td>
      <td>Smallpox, monkeypox</td>
    </tr>
    <tr>
      <th>35</th>
      <td>RNA</td>
      <td>LNP- encapsulated mRNA  cocktail encoding VLP</td>
      <td>Fudan University/ Shanghai JiaoTong University...</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>36</th>
      <td>RNA</td>
      <td>LNP- encapsulated mRNA encoding RBD</td>
      <td>Fudan University/ Shanghai JiaoTong University...</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>37</th>
      <td>RNA</td>
      <td>mRNA</td>
      <td>China CDC/Tongji University/Stermina</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>38</th>
      <td>RNA</td>
      <td>mRNA</td>
      <td>Arcturus/Duke-NUS</td>
      <td>Pre-Clinical</td>
      <td>multiple candidates</td>
    </tr>
    <tr>
      <th>39</th>
      <td>RNA</td>
      <td>mRNA</td>
      <td>BioNTech/Fosun Pharma/Pfizer</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>40</th>
      <td>RNA</td>
      <td>saRNA</td>
      <td>Imperial College London</td>
      <td>Pre-Clinical</td>
      <td>EBOV; LASV, MARV, Inf (H7N9), RABV</td>
    </tr>
    <tr>
      <th>41</th>
      <td>RNA</td>
      <td>mRNA</td>
      <td>Curevac</td>
      <td>Pre-Clinical</td>
      <td>RABV, LASV, YFV; MERS, InfA, ZIKV, DengV, NIPV</td>
    </tr>
    <tr>
      <th>42</th>
      <td>VLP</td>
      <td>Plant-derived VLP</td>
      <td>Medicago Inc.</td>
      <td>Pre-Clinical</td>
      <td>Flu, Rotavirus, Norovirus, West Nile virus, Ca...</td>
    </tr>
    <tr>
      <th>43</th>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>University of Hong Kong</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>44</th>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>ImmunoPrecise</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>45</th>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>MIGAL Galilee Research Institute</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>46</th>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>Doherty Institute</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>47</th>
      <td>Unknown</td>
      <td>Unknown</td>
      <td>Tulane University</td>
      <td>Pre-Clinical</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>


