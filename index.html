<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Grade Checker</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen">

    <div class="bg-white w-full max-w-md p-8 rounded-2xl shadow-lg">
        <div class="text-center mb-8">
            <h1 class="text-3xl font-bold text-gray-800">Student Grade Portal</h1>
            <p class="text-gray-500 mt-2">Select a term and enter your ID to check your grade.</p>
        </div>

        <div class="mb-4">
            <select id="termSelect" class="w-full px-4 py-3 border-2 bg-white border-gray-200 rounded-xl focus:outline-none focus:border-indigo-500 transition duration-300">
                <option value="prelim">Prelim</option>
                <option value="midterm">Midterm</option>
                <option value="prefinal">Pre-final</option>
                <option value="finals">Finals</option>
            </select>
        </div>

        <div class="flex w-full items-center border-2 border-gray-200 rounded-xl overflow-hidden">
            <span class="px-4 py-4 bg-gray-50 text-gray-500 font-medium whitespace-nowrap">2000</span>
            <input type="text" id="studentIdInput" placeholder="XXXXXX" class="w-full px-6 py-4 text-gray-700 placeholder-gray-400 focus:outline-none">
            <button id="checkGradeBtn" class="bg-indigo-600 text-white px-6 py-4 font-semibold hover:bg-indigo-700 transition duration-300 ease-in-out focus:outline-none">
                Check
            </button>
        </div>

        <div id="result" class="mt-8 text-center p-6 bg-gray-50 rounded-xl min-h-[120px] flex items-center justify-center">
             <p class="text-gray-500">Your grade will appear here.</p>
        </div>

        <p class="text-xs text-gray-400 text-center mt-6">
            <strong>Note:</strong> This is not an official grade portal. This is for DDC and SQA purposes only.
        </p>
    </div>

    <script>
        const studentData = {
            "2000248901": { name: "AQUINO,MICHELLE SARTILLO", grades: { prelim: { score: 95.33, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000423800": { name: "BACULO,BRANDON YULO CRUZ", grades: { prelim: { score: 88.83, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000349803": { name: "BALAGTAS,PRINCE BENEDICT JADONI", grades: { prelim: { score: 90.44, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000343634": { name: "BALLESTEROS,RAIN VINCENT MADAYAG", grades: { prelim: { score: 87.78, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000340706": { name: "BARIQUIT,REINYEIL JOHN CABILAN", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000268039": { name: "BINWAG,NOOR SAN GABRIEL", grades: { prelim: { score: 89.11, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000326292": { name: "BOQUERON,JEMUEL LLOBRERA", grades: { prelim: { score: 78.44, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000331540": { name: "BUENO,GABRIEL ISAAC STA INES", grades: { prelim: { score: 81.61, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000348170": { name: "COBARIA,SOFIA ELVINA", grades: { prelim: { score: 94.00, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000359021": { name: "COLARINA,ARMAND VIRGIL MORALES", grades: { prelim: { score: 77.11, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000361565": { name: "CRUZ,JOSIAH CHYEOJ MIGEL GONZALES", grades: { prelim: { score: 87.11, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000363659": { name: "DAVID,VENERABLE BELTRAN", grades: { prelim: { score: 72.28, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "10000111288": { name: "DELA CRUZ,KENNETH DELA LLANA", grades: { prelim: { score: 93.11, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000347095": { name: "DENOLA,NICA BELARMINO", grades: { prelim: { score: 92.67, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000343680": { name: "DILLO,ADRIENNE REYES", grades: { prelim: { score: 89.11, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000330206": { name: "DINO,ALDRIN QUIEN", grades: { prelim: { score: 89.11, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000433874": { name: "DUEÑAS,CEDRIC JIGGOR MENDOZA", grades: { prelim: { score: 89.11, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000354812": { name: "EUGENIO,ORVEN JAN RAYMUNDO", grades: { prelim: { score: 78.44, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000423797": { name: "GUATLO,RASSEL RAYYN MARCELINO", grades: { prelim: { score: 83.33, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000357223": { name: "IGLESIAS,KYLA JOY ABALOS", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000267435": { name: "MADRIAGA,ALDWIN KYLL DEQUIT", grades: { prelim: { score: 78.00, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000349178": { name: "MAYORMITA,JESS ARVEN HILUDO", grades: { prelim: { score: 93.11, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000255196": { name: "MENDOZA,JAIRUS RAIN PADILLA", grades: { prelim: { score: 93.11, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000253451": { name: "MIRANDA,FONZY KIEL BATOL", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000335567": { name: "NICOLAS,GABBY KHMIR ORTEA", grades: { prelim: { score: 93.11, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000337111": { name: "PEBRES,DAVE CHARLES SAMERA", grades: { prelim: { score: 90.44, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000341044": { name: "REVIDIZO,JANNA MIKAELA REYES", grades: { prelim: { score: 65.11, equivalent: 2.75 }, midterm: null, prefinal: null, finals: null } },
            "2000330964": { name: "RUIZ,EARL DANIEL DELA CRUZ", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000369860": { name: "SAAC,JOHN PAUL LEGASPI", grades: { prelim: { score: 93.11, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000325381": { name: "SANGALANG,NEO BACLAAN", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000379923": { name: "SANTOS,BIGBHOY ALFRENZ ENRIQUEZ", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000344035": { name: "SITU,CHARLES RICHARD OROBIA", grades: { prelim: { score: 90.44, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000423974": { name: "SONIO,CLARENCE NODA", grades: { prelim: { score: 77.78, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000293188": { name: "SUERO,JOHN GREGORY ACUÑA", grades: { prelim: { score: 81.11, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000226661": { name: "TUMON,MARK VINCENT VILLARINO", grades: { prelim: { score: 75.78, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000348562": { name: "VALDEZ,JOHN CARLO FELICIANO", grades: { prelim: { score: 75.78, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000350798": { name: "VILLANUEVA,JOCO", grades: { prelim: { score: 78.44, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000348275": { name: "VILLANUEVA,VINCENT IVAN GALSIM", grades: { prelim: { score: 89.11, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000347235": { name: "VITENIO,ANDREI DAYON", grades: { prelim: { score: 91.78, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000362749": { name: "AGUILAR,EZEKIEL RAVEN VILLAR", grades: { prelim: { score: 90.00, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000369180": { name: "BERNARDO,ADRIAN CRUZ", grades: { prelim: { score: 96.67, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000153978": { name: "BOLAÑOS,SAMUEL JACOB MAMARIL", grades: { prelim: { score: 94.67, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000223062": { name: "BUGARIN,RENZY ADRA", grades: { prelim: { score: 73.11, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000368441": { name: "CABAYAO,WILLIAM CEDRIC CATUNGAL", grades: { prelim: { score: 79.33, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000274960": { name: "CENCIO,KURT ZHAIROL MAIQUEZ", grades: { prelim: { score: 84.44, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000365501": { name: "COLLADO,MA. GHEMXIE GAMBONG", grades: { prelim: { score: 63.33, equivalent: 3.00 }, midterm: null, prefinal: null, finals: null } },
            "2000373534": { name: "CREADO,MARK JOHN MARTINEZ", grades: { prelim: { score: 78.00, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000368469": { name: "DACUMOS,PAUL GABRIEL MORALES", grades: { prelim: { score: 92.67, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000369183": { name: "DE LUNA,JADE KERBY CANONIYO", grades: { prelim: { score: 79.78, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000323228": { name: "DOROMAL,ACKERLEY GABRIEL CREMEN", grades: { prelim: { score: 67.33, equivalent: 2.75 }, midterm: null, prefinal: null, finals: null } },
            "2000376084": { name: "ELCANO,JOHAN FLOYD RUGAS", grades: { prelim: { score: 74.00, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000361897": { name: "FABIALA,LEBRON JAMES PANESALES", grades: { prelim: { score: 87.33, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000375957": { name: "GARCIA,HANNAH GRACE RUIZ", grades: { prelim: { score: 83.33, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000372499": { name: "GUANISO,JOHN DWAYNE BUATAG", grades: { prelim: { score: 78.00, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000321690": { name: "GUIAMAN,JULIA BELLO", grades: { prelim: { score: 83.33, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000135723": { name: "HORARIO,JAMES RYAN PELAYO", grades: { prelim: { score: 95.33, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000370125": { name: "HULAR,HILARY CONCEPCION", grades: { prelim: { score: 91.33, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000266247": { name: "IBUNA,VAN HARLEY CRUZ", grades: { prelim: { score: 90.00, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000325139": { name: "INGUITO,RAPHAEL VINCENT RECATO", grades: { prelim: { score: 75.33, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000273268": { name: "JADULCO,PAUL JADE PAULITE", grades: { prelim: { score: 86.00, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000341517": { name: "JIMENEZ,JOSHUA MARTINEZ", grades: { prelim: { score: 94.00, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000344679": { name: "LAGUARDIA,SAMANTHA NICOLE GALBOSO", grades: { prelim: { score: 92.67, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000362404": { name: "MINGLANILLA,JOSHUA GAIL DIMABILDO", grades: { prelim: { score: 91.33, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000370248": { name: "MORAL,THEUS NIGEL CONSORTE", grades: { prelim: { score: 87.33, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000361787": { name: "MUEGA,LANCE CHESTER LANON", grades: { prelim: { score: 84.67, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000367145": { name: "ORENDAIN,CHRISTIAN LESTER PERALTA", grades: { prelim: { score: 90.00, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000376867": { name: "REGULACION,RAIN JAMOLIN", grades: { prelim: { score: 88.67, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000376003": { name: "ROBLES,VANESSA ANGEL CASTILLO", grades: { prelim: { score: 91.33, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000369584": { name: "RUMBAOA,ANDREI JEFFERSON JAPAY", grades: { prelim: { score: 87.33, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000327685": { name: "SALVAN,JIRO ALVAREZ", grades: { prelim: { score: 86.00, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000427651": { name: "SAN LUIS,JOHN FRANCIS MIGUEL", grades: { prelim: { score: 65.11, equivalent: 2.75 }, midterm: null, prefinal: null, finals: null } },
            "2000322700": { name: "SAYSON,MARK JASON CORRAL", grades: { prelim: { score: 84.67, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000418324": { name: "SORIANO,GHERICO BUENAAGUA", grades: { prelim: { score: 95.33, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000256939": { name: "TOLEDO,RIEZL LOUICE", grades: { prelim: { score: 84.67, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000345049": { name: "TORIDA,CLYDE LOUISE DE GUZMAN", grades: { prelim: { score: 94.00, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000363191": { name: "VERGARA,EHDRIAN ESTEBAN", grades: { prelim: { score: 94.00, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000367387": { name: "ADONIS,LEE RYAN EMMANUEL VALERIANO", grades: { prelim: { score: 96.47, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000334153": { name: "ALONZO,ROLAND BENJAMIN JOSE", grades: { prelim: { score: 95.13, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000333102": { name: "ANTONIO,KIESHA CYRA CAJEPE", grades: { prelim: { score: 80.97, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000369497": { name: "ARTATEZ,DANILO JR. TABUNDA", grades: { prelim: { score: 84.30, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000262048": { name: "AUGUSTO,MARK JOHN", grades: { prelim: { score: 79.97, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000378025": { name: "BAÑAS,JHUZTINE PALAFOX", grades: { prelim: { score: 93.80, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000355468": { name: "BINAMIRA,MARL KIAN", grades: { prelim: { score: 86.30, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000409644": { name: "BUENAAGUA,KAIZAN COLEEN SAN ANDRES", grades: { prelim: { score: 83.13, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000346826": { name: "CAJILIG,GYLL CLAUDETTE BERNAL", grades: { prelim: { score: 85.80, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000346696": { name: "CALIWAG,JAN MARTIN BARTILET", grades: { prelim: { score: 92.63, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000353607": { name: "CITRA,ALFRED BERNARD CONEJERO", grades: { prelim: { score: 89.00, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000358061": { name: "DADAP,CARLOS MIGUEL CAMILO", grades: { prelim: { score: 94.17, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000328828": { name: "DE VERA,JENEL YUGING", grades: { prelim: { score: 95.13, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000373803": { name: "ESCOBIA,JOHNNY JAMES ALAVAZO", grades: { prelim: { score: 87.63, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000367374": { name: "ESPANUEVA,FRANCES LUISA OCAMPO", grades: { prelim: { score: 96.47, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000346847": { name: "FERNANDEZ,JOHN KAYE PARANAS", grades: { prelim: { score: 96.47, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000249561": { name: "FERNANDO,FRANCHESKCA ARROYO", grades: { prelim: { score: 96.47, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000356647": { name: "GAJUDO,JHON VINCENT BORROMEO", grades: { prelim: { score: 82.30, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000419912": { name: "GONZALES,JUL JIMMY SADJAIL", grades: { prelim: { score: 92.63, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000349594": { name: "MAGALLON,JOHN CARLO DEBOSURA", grades: { prelim: { score: 95.13, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000367094": { name: "MARISCAL,FRANCIS MAÑARES", grades: { prelim: { score: 83.63, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000344587": { name: "MEGANO,MARGARET CANICULA", grades: { prelim: { score: 77.30, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000345383": { name: "MENDOZA,KENDRICK BRYCE VILLANUEVA", grades: { prelim: { score: 79.63, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000350657": { name: "MONTE,MON DENZEL ATENCIO", grades: { prelim: { score: 88.97, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000335989": { name: "NOLASCO,JUSTIN JABIL", grades: { prelim: { score: 95.13, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000356838": { name: "OLIVER,ERVIN JOSEPH SERRANO", grades: { prelim: { score: 93.80, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000364413": { name: "ORTEGA,QUASAR MAXX DE GUZMAN", grades: { prelim: { score: null, equivalent: 'Inc' }, midterm: null, prefinal: null, finals: null } },
            "2000356739": { name: "OSEÑA,JOSEPH CASTILLO", grades: { prelim: { score: 94.17, equivalent: 1.50 }, midterm: null, prefinal: null, finals: null } },
            "2000332445": { name: "PAYOD,SHAIRA GAILE VALERIO", grades: { prelim: { score: 89.80, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000372076": { name: "RAMOS,CATHERINE GEBE", grades: { prelim: { score: 87.63, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000355734": { name: "REYES,MERK ANDREI BRAGADO", grades: { prelim: { score: 84.17, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000245745": { name: "SACAY,ANDREI GERICO BENEDICTOS", grades: { prelim: { score: 96.47, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000357825": { name: "SANTOS,JOAQUIN GABRIEL ABILLON", grades: { prelim: { score: 95.13, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000360294": { name: "SENOC,MAVI DEN GAEDRELL MONTANIEL", grades: { prelim: { score: 77.13, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000321473": { name: "SESE,ALROGER NODA", grades: { prelim: { score: 82.83, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000346334": { name: "TABLADA,JEROME GAVIOLA", grades: { prelim: { score: 84.97, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000373058": { name: "VILLANUEVA,JOSHUA LEONARD DELA ROSA", grades: { prelim: { score: 86.97, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000329154": { name: "VILLAS,MARY DAYNE TEJOSO", grades: { prelim: { score: 95.13, equivalent: 1.25 }, midterm: null, prefinal: null, finals: null } },
            "2000371996": { name: "VINCER,JOHN HOWARD BAÑARES", grades: { prelim: { score: 83.63, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000213330": { name: "AGUILAR,ARMEL JAMES MABIOG", grades: { prelim: { score: 80.67, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000152881": { name: "ARAGON,BENJAMIN DELA CRUZ", grades: { prelim: { score: 61.58, equivalent: 3.00 }, midterm: null, prefinal: null, finals: null } },
            "2000221701": { name: "ARROYO,PRINCE RILLEY FERNANADEZ", grades: { prelim: { score: 67.17, equivalent: 2.75 }, midterm: null, prefinal: null, finals: null } },
            "2000306434": { name: "ATIENZA,ISAIAH JESSIE", grades: { prelim: { score: 90.83, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000300656": { name: "BELLEZA,JANE WILLE ROQUERO", grades: { prelim: { score: 75.67, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000280224": { name: "BUTIL,GHIANNE GERALD CASTILLO", grades: { prelim: { score: 73.67, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000292453": { name: "CAGAPE,JOHN MATTHEW MERCADO", grades: { prelim: { score: 61.33, equivalent: 3.00 }, midterm: null, prefinal: null, finals: null } },
            "2000309575": { name: "DE GRACIA,TRISHA ANNE ORQUEJO", grades: { prelim: { score: 65.83, equivalent: 2.75 }, midterm: null, prefinal: null, finals: null } },
            "2000313242": { name: "GARCIA,RHENIEL JACOB LLOBRERA", grades: { prelim: { score: 74.25, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000287206": { name: "ISMAEL,JUCE YUTIGA", grades: { prelim: { score: 60.42, equivalent: 3.00 }, midterm: null, prefinal: null, finals: null } },
            "2000316126": { name: "JIMENEZ,CHARLHANN DAMASCO", grades: { prelim: { score: 87.50, equivalent: 1.75 }, midterm: null, prefinal: null, finals: null } },
            "2000320249": { name: "JOSE,KIRSTEN MACARAYAN", grades: { prelim: { score: 64.17, equivalent: 3.00 }, midterm: null, prefinal: null, finals: null } },
            "2000300887": { name: "MERCADO,JELMAR CASAS", grades: { prelim: { score: 83.67, equivalent: 2.00 }, midterm: null, prefinal: null, finals: null } },
            "2000224538": { name: "REALOZA,KATHLEEN ESCORIAL", grades: { prelim: { score: 65.67, equivalent: 2.75 }, midterm: null, prefinal: null, finals: null } },
            "2000307235": { name: "ROSARIO,JUSTINE FELLIZAR", grades: { prelim: { score: 78.83, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000298999": { name: "SOLIGUEN,ANDREW MIGUEL RUMBAWA", grades: { prelim: { score: 77.83, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000295662": { name: "TACBAD,SAMANTHA GRACE TEVES", grades: { prelim: { score: 80.33, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } },
            "2000319243": { name: "TAMAYO,JENICA IRIS GUEVARA", grades: { prelim: { score: 72.50, equivalent: 2.50 }, midterm: null, prefinal: null, finals: null } },
            "2000317021": { name: "VELASCO,SEANN HEDRIX LAGUIO", grades: { prelim: { score: 80.67, equivalent: 2.25 }, midterm: null, prefinal: null, finals: null } }
        };

        const studentIdInput = document.getElementById('studentIdInput');
        const checkGradeBtn = document.getElementById('checkGradeBtn');
        const resultDiv = document.getElementById('result');
        const termSelect = document.getElementById('termSelect');

        const displayResult = (student, term) => {
            if (student) {
                const gradeData = student.grades[term];
                if (gradeData !== null && gradeData !== undefined) {
                    const score = gradeData.score;
                    const equivalent = gradeData.equivalent;

                    if (score !== null && score !== undefined) {
                        resultDiv.innerHTML = `
                            <div class="text-left w-full">
                                <p class="text-lg text-gray-800"><span class="font-semibold">Name:</span> ${student.name}</p>
                                <p class="text-md text-gray-600 capitalize"><span class="font-semibold">Term:</span> ${term.replace('prefinal', 'Pre-final')}</p>
                                <div class="flex justify-around items-baseline mt-2 text-center">
                                    <div>
                                        <p class="text-xs text-gray-500 uppercase font-medium tracking-wider">Grade</p>
                                        <p class="text-4xl font-bold ${score >= 75 ? 'text-green-500' : 'text-red-500'}">${score.toFixed(2)}</p>
                                    </div>
                                    <div>
                                        <p class="text-xs text-gray-500 uppercase font-medium tracking-wider">Equivalent</p>
                                        <p class="text-4xl font-bold ${score >= 75 ? 'text-green-500' : 'text-red-500'}">${typeof equivalent === 'number' ? equivalent.toFixed(2) : equivalent}</p>
                                    </div>
                                </div>
                            </div>
                        `;
                    } else { // Handle cases like 'Inc' where score is null
                        resultDiv.innerHTML = `
                            <div class="text-left w-full">
                                <p class="text-lg text-gray-800"><span class="font-semibold">Name:</span> ${student.name}</p>
                                <p class="text-md text-gray-600 capitalize"><span class="font-semibold">Term:</span> ${term.replace('prefinal', 'Pre-final')}</p>
                                <p class="text-2xl text-yellow-600 font-semibold mt-2">Grade: ${equivalent}</p>
                            </div>
                        `;
                    }
                } else {
                    resultDiv.innerHTML = `
                     <div class="text-left w-full">
                        <p class="text-lg text-gray-800"><span class="font-semibold">Name:</span> ${student.name}</p>
                        <p class="text-yellow-600 font-semibold mt-2">Grade for this term is not yet available.</p>
                    </div>`;
                }
            } else {
                 resultDiv.innerHTML = `<p class="text-red-500 font-semibold">Student ID not found. Please try again.</p>`;
            }
        };

        const checkGrade = () => {
            const studentIdSuffix = studentIdInput.value.trim();
            const selectedTerm = termSelect.value;
            if (studentIdSuffix) {
                // Combine the prefilled part with the user's input
                const studentId = "2000" + studentIdSuffix;
                const student = studentData[studentId];
                displayResult(student, selectedTerm);
            } else {
                resultDiv.innerHTML = `<p class="text-gray-500">Please enter the remaining digits of your Student ID.</p>`;
            }
        };

        checkGradeBtn.addEventListener('click', checkGrade);
        studentIdInput.addEventListener('keyup', (event) => {
            if (event.key === 'Enter') {
                checkGrade();
            }
        });
        termSelect.addEventListener('change', checkGrade);


    </script>

</body>
</html>

