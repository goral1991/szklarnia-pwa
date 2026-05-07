<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
  <title>Sterowanie podlewaniem szklarni</title>

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
  <!-- Bootstrap Icons -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet" />

  <!-- Manifest i PWA -->
  <link rel="manifest" href="manifest.json" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <meta name="mobile-web-app-capable" content="yes">
   
  <!-- Chart.js  -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

  <!-- Chart.js Zoom Plugin -->
<script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-zoom@2.0.1/dist/chartjs-plugin-zoom.min.js"></script>

  <!-- Flat pickr -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/flatpickr/dist/flatpickr.min.css">
<script src="https://cdn.jsdelivr.net/npm/flatpickr"></script>
<script src="https://cdn.jsdelivr.net/npm/flatpickr@4.6.13/dist/l10n/pl.js"></script>

  <!-- Leaflet CSS -->
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />

    

  
<link rel="stylesheet" href="style.css" />

<link rel="icon" type="image/png" sizes="32x32" href="icons/favicon-32x32.png" />


</head>
<body class="d-flex flex-column justify-content-start align-items-center">

<!-- Nagłówek -->
<div class="safe-top w-100 px-3">
  <div class="d-flex justify-content-between align-items-center">
  <h1 class="logo-text m-0 d-flex align-items-center gap-2">
  Szklarnia
 <span id="heartbeatDot" class="rounded-circle bg-secondary" style="width:12px; height:12px; display:inline-block;"></span>
<span id="updateText" style="margin-left: 0px; font-size: 8px; "></span>
</h1>


<div class="dropdown">
  <button class="btn p-0 three-dots-btn" id="menuDropdownBtn" data-bs-toggle="dropdown" aria-expanded="false">
    <i class="bi bi-three-dots-vertical fs-4"></i>
  </button>
  <ul class="dropdown-menu dropdown-menu-end" id="themeDropdown">
    <li>
      <a class="dropdown-item" href="#" id="themeToggle">
        <i class="bi bi-sun" id="themeIcon"></i> Tryb motywu
      </a>
    </li>
    <li>
      <a class="dropdown-item" href="#" data-bs-toggle="modal" data-bs-target="#infoModal">
        <i class="bi bi-info-circle"></i> Informacje
      </a>
    </li>
    <li>
      <a class="dropdown-item" href="#" data-bs-toggle="modal" data-bs-target="#modalMap">
        <i class="bi bi-cloud-sun"></i> Dane pogodowe
      </a>
    </li>
  </ul>
</div>



  </div>
</div>


 <!-- Sekcja pogody  -->  <h4 class="schedule-title px-3">POGODA</h4>
<div class="container-weather d-flex flex-row justify-content-between align-items-start gap-2 mt-3 px-3" style="max-width: 1000px; margin: 0 auto;">

<!-- Lewa: aktualna pogoda -->
<div class="glass-currentweather p-2 text-center current-weather" style="flex: 0 0 auto;">
  <div class="fw-bold mb-1">Teraz</div>
  <img id="currentIcon" src="" alt="pogoda" >
  <div id="currentTempWeather" style="font-size: 1rem;">--°C</div>
  
  
</div>

  <!-- Prawa kolumna: prognoza -->
  <div class="weather-forecast d-flex flex-nowrap overflow-auto gap-2 px-1" style="flex: 1;">
    <!-- Kafelki prognozy pojawią się tutaj przez JS -->
  </div>

</div>





<!-- Kafelki temperatura i wilgotność -->
<div class="d-flex flex-column align-items-center mt-4 gap-3 w-100 px-3">

  <h4 class="schedule-title px-3">DANE ZE SZKLARNI</h4>

  <!-- Temperatura -->
  <div class="tile glass-tile sensor-tile d-flex justify-content-between align-items-center p-3 w-100">
    <div class="label">
      <i class="bi bi-thermometer-half"></i>
      <span>Temperatura szklarni</span>
    </div>
    <div class="d-flex align-items-center gap-2">
      <div class="value" id="tempTile">...</div>
      <i class="bi bi-three-dots-vertical more-icon"></i>
    </div>
  </div>

  <!-- Wilgotność powietrza -->
  <div class="tile glass-tile sensor-tile d-flex justify-content-between align-items-center p-3 w-100">
    <div class="label">
      <i class="bi bi-droplet-half"></i>
      <span>Wilgotność szklarni</span>
    </div>
    <div class="d-flex align-items-center gap-2">
      <div class="value" id="humTile">...</div>
      <i class="bi bi-three-dots-vertical more-icon"></i>
    </div>
  </div>
  
  <!-- Wilgotność gleby -->
  <div class="tile glass-tile sensor-tile d-flex justify-content-between align-items-center p-3 w-100">
    <div class="label">
      <i class="bi bi-droplet"></i>
      <span>Wilgotność gleby</span>
    </div>
    <div class="d-flex align-items-center gap-2">
      <div class="value" id="glebaTile">...</div>
      <i class="bi bi-three-dots-vertical more-icon"></i>
    </div>
  </div>

</div>


<!-- Nowoczesne dolne menu z podpisami -->
<nav class="bottom-nav">
  <div class="nav-item left">
    <button class="nav-icon" id="scheduleBtn">
      <i class="bi bi-calendar-event-fill"></i>
    </button>
    <div class="nav-label">Dodaj plan</div>
  </div>

  <div class="main-button-wrapper">
    <button id="valveBtn" class="main-btn shadow-lg">Podlej</button>
  </div>
  


<div class="nav-item right">
  <button class="nav-icon" id="historyBtn">
    <i class="bi bi-clock-history"></i>
  </button>
  <div class="nav-label">Historia</div>
</div>

</nav>


<!-- Formularz dodawania do harmonogramu -->
<div class="modal fade show" id="scheduleModal" tabindex="-1" aria-labelledby="scheduleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-lg">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header">
        <h5 class="modal-title" id="scheduleModalLabel">Dodaj harmonogram podlewania</h5>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Zamknij"></button>
      </div>
      <div class="modal-body">
        <form id="scheduleForm" class="row g-3 align-items-center">
          <div class="col-12 col-md-4">
            <label for="weekday" class="form-label">Dzień tygodnia</label>
            <select id="weekday" class="form-select" required>
              <option value="" disabled selected>Wybierz dzień</option>
              <option value="1">Poniedziałek</option>
              <option value="2">Wtorek</option>
              <option value="3">Środa</option>
              <option value="4">Czwartek</option>
              <option value="5">Piątek</option>
              <option value="6">Sobota</option>
              <option value="0">Niedziela</option>
            </select>
          </div>
          <div class="col-12 col-md-4">
            <label for="startTime" class="form-label">Godzina rozpoczęcia podlewania</label>
            <input type="time" id="startTime" class="form-control" required>
          </div>
          <div class="col-12 col-md-4">
            <label for="endTime" class="form-label">Godzina zakończenia podlewania</label>
            <input type="time" id="endTime" class="form-control" required>
          </div>
          <div class="col-12 text-center">
            <button type="submit" class="btn btn-secondary px-5">Zapisz</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>


<!-- Modal z MAPA -->
<!-- Modal z MAPA -->
<div class="modal fade" id="modalMap" tabindex="-1" aria-labelledby="modalMapLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header">
        <h5 class="modal-title" id="modalMapLabel">Wybierz lokalizację</h5>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div id="mapModal" style="height: 300px;"></div> <!-- Mapa -->
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Anuluj</button>
        <button type="button" class="btn btn-primary" id="saveLocation">Zapisz lokalizację</button>
      </div>
    </div>
  </div>
</div>




<!-- Modal Informacje -->
<div class="modal fade show" id="infoModal" tabindex="-1" aria-labelledby="infoModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header">
        <h5 class="modal-title" id="infoModalLabel">Informacje o aplikacji</h5>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Zamknij"></button>
      </div>
      <div class="modal-body">
        <p>Aplikacja do sterowania podlewaniem szklarni.</p>
        <p><strong>Twórca:</strong> Piotr Górajewski</p>
        <p><strong>Kontakt:</strong> <a href="mailto:piotrgorajewski@gmail.com" class="link-light">piotrgorajewski@gmail.com</a></p>
      </div>
    </div>
  </div>
</div>
<br>
<!-- Lista harmonogramu -->

<h4 class="schedule-title">Harmonogram podlewania</h4>
<div class="schedule-list w-100 px-3" style="max-width:600px;">
  <div id="scheduleItems">
    <!-- tutaj będą wpisy -->
  </div>
</div>






<div class="modal fade show" id="chartModal" tabindex="-1" aria-labelledby="chartModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-lg">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header">
        <h6 class="modal-title" id="chartModalLabel">Wykres</h6>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Zamknij"></button>
      </div>
      <div class="modal-body">
        <canvas id="sensorChart" height="300px"></canvas>

        <!-- Kafelki pod wykresem -->
        <div class="d-flex justify-content-between gap-3 mt-4">
          <div class="flex-fill p-3 rounded-3" style="background-color: #2a2a2a;">
            <div class="small">Aktualny odczyt</div>
            <div class="fw-semibold fs-6" id="currentTemp">-- °C</div>
          </div>
          <div class="flex-fill p-3 rounded-3" style="background-color: #2a2a2a;">
            <div class="small">Min / Max (24h)</div>
            <div class="fw-semibold fs-6" id="minMaxTemp">-- / -- °C</div>
          </div>
        </div>
        <!-- Koniec kafelków -->

      </div>
    </div>
  </div>
</div>




<!-- Modal podlewania -->
<div class="modal fade show" id="wateringModal" tabindex="-1" aria-labelledby="wateringModalLabel" aria-hidden="true" data-backdrop="static">
  <div class="modal-dialog modal-dialog-centered">
    <div class="modal-content text-center p-3">
      <h5 id="wateringModalLabel">Podlewanie w toku</h5>
      <div style="font-size: 2em; font-weight: bold;" id="wateringTimer">00:00</div>
      <button type="button" class="btn btn-secondary mt-3" id="closeWateringModalBtn">Anuluj</button>
    </div>
  </div>
</div>

<!-- Modal historia podlewania -->
<div class="modal fade show" id="historyModal" tabindex="-1" aria-labelledby="historyModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-lg">
    <div class="modal-content bg-dark text-white">
      <div class="modal-header">
        <h5 class="modal-title" id="historyModalLabel">Historia podlewania</h5>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Zamknij"></button>
      </div>

      <div class="modal-body">
        <div class="d-flex justify-content-center mb-1"><!-- zmniejszony margines -->
          <div id="historyCalendar"></div>
        </div>
                <p class="mt-3 text-center text-white-50" style="font-weight: 600;">
          LISTA ZAŁĄCZEŃ PODLEWANIA
        </p>
        <ul class="list-group" id="historyList"></ul>

      </div>

    </div>
  </div>
</div>





<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>


<!-- Załaduj jQuery przed innymi skryptami -->
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>



<!-- Leaflet JS -->
<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>


<script>
  if ('serviceWorker' in navigator) {
    navigator.serviceWorker.register('sw.js')
      .then(reg => console.log('Service Worker zarejestrowany', reg))
      .catch(err => console.error('Błąd rejestracji SW', err));
  }
</script>



<script>
  const supabaseUrl = "https://xnslhprzbygutwfyazsx.supabase.co/rest/v1";
  const apiKey = "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6Inhuc2xocHJ6YnlndXR3ZnlhenN4Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3NDk0NjcwNjQsImV4cCI6MjA2NTA0MzA2NH0.BP7KKN9UU4f_zQ1rMiTupkl7S19pLnnYnxhAxNpZ1FE";
  const recordId = 1;
  let currentState = null;

  const valveBtn = document.getElementById('valveBtn');
  const tempTile = document.getElementById('tempTile');
  const humTile = document.getElementById('humTile');
  const glebaTile = document.getElementById('glebaTile');

  // ELEMENTY FORMULARZA
  const scheduleForm = document.getElementById('scheduleForm');
  const weekdaySelect = document.getElementById('weekday');
  const startTimeInput = document.getElementById('startTime');
  const endTimeInput = document.getElementById('endTime');
  const scheduleItemsContainer = document.getElementById('scheduleItems');

  // Pomocnicza funkcja do formatowania czasu hh:mm
  function formatTime(hour, minute) {
    return String(hour).padStart(2, '0') + ':' + String(minute).padStart(2, '0');
  }

  // Pokazuje przyjazną nazwę dnia
  function weekdayName(num) {
    const names = {
      1: "Poniedziałek",
      2: "Wtorek",
      3: "Środa",
      4: "Czwartek",
      5: "Piątek",
      6: "Sobota",
      0: "Niedziela"
    };
    return names[num] || "";
  }

  // Aktualizacja przycisku sterowania zaworem
function updateButton() {
  valveBtn.disabled = false;
  if (currentState) {
    valveBtn.innerHTML = `
      <i class="bi bi-droplet" style="font-size: 1.5em; display: block; margin-bottom: 4px;"></i>
      <span>Podlewanie</span>
    `;
    valveBtn.classList.remove('btn-success');
    valveBtn.classList.add('btn-open');
  } else {
    valveBtn.innerHTML = `
      <i class="bi bi-droplet" style="font-size: 1.5em; display: block; margin-bottom: 4px;"></i>
      <span>Podlej</span>
    `;
    valveBtn.classList.remove('btn-open');
    valveBtn.classList.add('btn-success');
  }
}
  
  

  // Pobierz stan zaworu
  async function fetchValveState() {
    try {
      const res = await fetch(`${supabaseUrl}/status?select=valve_state&id=eq.${recordId}`, {
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`
        }
      });
      const data = await res.json();
      if (data.length > 0 && data[0].valve_state !== currentState) {
        currentState = data[0].valve_state;
        updateButton();
      }
    } catch (e) {
      valveBtn.textContent = "Błąd połączenia";
      valveBtn.disabled = true;
      console.error(e);
    }
  }

  // Pobierz dane sensorów temperatury i wilgotności
// Twoja istniejąca funkcja - bez zmian
async function fetchSensorData() {
  try {
    const res = await fetch(`${supabaseUrl}/czujniki?select=temperatura,wilgotnosc,wilgotnosc_gleby,data_czas&order=data_czas.desc&limit=1`, {
      headers: {
        apikey: apiKey,
        Authorization: `Bearer ${apiKey}`
      }
    });
    const data = await res.json();
    if (data.length > 0) {
      tempTile.textContent = ` ${data[0].temperatura.toFixed(1)} °C`;
      humTile.textContent = ` ${data[0].wilgotnosc.toFixed(1)} %`;
      glebaTile.textContent = ` ${data[0].wilgotnosc_gleby.toFixed(1)} %`;

      // Sprawdzenie daty i czasu
      const lastTimestamp = new Date(data[0].data_czas).getTime(); // UTC
      const now = Date.now(); // też UTC
      const diffSeconds = Math.floor((now - lastTimestamp) / 1000);

      const dot = document.getElementById('heartbeatDot');
      const updateText = document.getElementById('updateText');

      if (dot && updateText) {
        if (diffSeconds <= 90) {
          dot.classList.add('bg-success');
          dot.classList.remove('bg-danger');
        } else {
          dot.classList.add('bg-danger');
          dot.classList.remove('bg-success');
        }

        const diffMinutes = Math.floor(diffSeconds / 60);
        updateText.textContent = `(${diffMinutes} minut temu)`;

        console.log("Ostatni odczyt:", data[0].data_czas);
        console.log("Różnica czasów (s):", diffSeconds);
      }
    }
  } catch (e) {
    tempTile.textContent = "Błąd odczytu";
    humTile.textContent = "Błąd odczytu";
    glebaTile.textContent = "Błąd odczytu";
    console.error(e);
  }
}

async function fetchChartTileData(sensorType) {
  try {
    // Budujemy dynamiczny select na podstawie sensorType
    const res = await fetch(`${supabaseUrl}/czujniki?select=${sensorType},data_czas&order=data_czas.desc&limit=1000`, {
      headers: {
        apikey: apiKey,
        Authorization: `Bearer ${apiKey}`
      }
    });

    const data = await res.json();

    if (!data || data.length === 0) return;

    const now = Date.now();
    const cutoff = now - 24 * 60 * 60 * 1000; // 24 godziny wstecz

    // Filtrowanie pomiarów z ostatnich 24h
    const filtered = data.filter(entry => new Date(entry.data_czas).getTime() >= cutoff);

    if (filtered.length === 0) return;

    // Aktualna wartość = najnowszy wpis
    const current = filtered[0][sensorType];

    // Min i max z ostatnich 24h
    const values = filtered.map(d => d[sensorType]);
    const min = Math.min(...values);
    const max = Math.max(...values);

    // Jednostka
    const unit = (sensorType === 'temperatura') ? '°C' : '%';

    // Uzupełniamy kafelki w modalu
    document.getElementById('currentTemp').textContent = `${current.toFixed(1)} ${unit}`;
    document.getElementById('minMaxTemp').textContent = `${min.toFixed(1)} / ${max.toFixed(1)} ${unit}`;

  } catch (err) {
    console.error('Błąd podczas pobierania danych do kafelków modala:', err);
    document.getElementById('currentTemp').textContent = 'Błąd';
    document.getElementById('minMaxTemp').textContent = 'Błąd';
  }
}


  

  // Przełącz stan zaworu
  async function toggleValve() {
    valveBtn.disabled = true;
    valveBtn.textContent = 'Aktualizacja...';

    const newState = !currentState;

    try {
      const res = await fetch(`${supabaseUrl}/status?id=eq.${recordId}`, {
        method: 'PATCH',
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`,
          'Content-Type': 'application/json'
        },
        body: JSON.stringify({ valve_state: newState })
      });

      if (!res.ok) throw new Error('Błąd zmiany stanu');
      currentState = newState;
      updateButton();
    } catch (e) {
      alert("Nie udało się zmienić stanu zaworu");
      console.error(e);
      updateButton();
    }
  }

  valveBtn.addEventListener('click', toggleValve);

  // Dodaj wpis do harmonogramu
  scheduleForm.addEventListener('submit', async (e) => {
    e.preventDefault();

    // Pobierz wartości
  const weekday = weekdaySelect.value; 
    const startTime = startTimeInput.value; // "HH:MM"
    const endTime = endTimeInput.value;

if (
  weekday === "" ||
  startTime === "" ||
  endTime === ""
) {
  alert("Wypełnij wszystkie pola");
  return;
}

    // Rozbij start i end time na hour i minute
    const [startHour, startMinute] = startTime.split(':').map(Number);
    const [endHour, endMinute] = endTime.split(':').map(Number);

    // Do supabase dodajemy 2 wpisy: start podlewania valve_state=true, koniec valve_state=false
    try {
      // Start podlewania
      let res1 = await fetch(`${supabaseUrl}/harmonogram`, {
        method: 'POST',
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`,
          'Content-Type': 'application/json'
        },
        body: JSON.stringify({
          weekday: weekday,
          hour: startHour,
          minute: startMinute,
          valve_state: true,
          executed: false
        })
      });
      if (!res1.ok) throw new Error('Błąd zapisu startu');

      // Koniec podlewania
      let res2 = await fetch(`${supabaseUrl}/harmonogram`, {
        method: 'POST',
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`,
          'Content-Type': 'application/json'
        },
        body: JSON.stringify({
          weekday: weekday,
          hour: endHour,
          minute: endMinute,
          valve_state: false,
          executed: false
        })
      });
      if (!res2.ok) throw new Error('Błąd zapisu końca');

      alert('Wpis dodany do harmonogramu!');
      scheduleForm.reset();
      await fetchSchedule();
    } catch (err) {
      alert('Błąd podczas dodawania wpisu');
      console.error(err);
    }
  });

  // Pobierz harmonogram i wyświetl
  async function fetchSchedule() {
    try {
      const res = await fetch(`${supabaseUrl}/harmonogram?order=weekday, hour, minute`, {
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`
        }
      });
      const data = await res.json();

      // Przetworzymy dane, by pogrupować start i koniec podlewania po dniu i godzinach
      // Założenie: start = valve_state=true, koniec = valve_state=false

      // Grupujemy wpisy po dniu i dopasowujemy start i koniec
      const grouped = {};

      data.forEach(item => {
        const key = item.weekday + '-' + item.hour + '-' + item.minute;
        if (!grouped[item.weekday]) grouped[item.weekday] = [];
        grouped[item.weekday].push(item);
      });

      // Będziemy tworzyć wpisy z startem i końcem
      const scheduleByDay = {};



      // Utwórz tablicę z par start/stop dla każdego dnia
      const schedulePairs = {};

      // Przefiltruj na dni
      for(let day=0; day<=6; day++){
        schedulePairs[day] = [];
        const dayEntries = data.filter(d=>d.weekday===day).sort((a,b) => (a.hour*60 + a.minute) - (b.hour*60 + b.minute));
        // Znajdujemy pary start/stop
        for(let i=0; i<dayEntries.length; i++){
          const entry = dayEntries[i];
          if(entry.valve_state === true){
            // Szukamy kolejnego valve_state=false o tym samym dniu i większym czasie
            let endEntry = dayEntries.find(d => d.valve_state === false && (d.hour*60 + d.minute) > (entry.hour*60 + entry.minute));
            if(endEntry){
              schedulePairs[day].push({start: entry, end: endEntry});
            } else {
              schedulePairs[day].push({start: entry, end: null});
            }
          }
        }
      }

      // Wyczyść listę
      scheduleItemsContainer.innerHTML = '';

      // Dodaj wpisy w czytelnej formie z przyciskiem usuń
      for(let day=0; day<=6; day++){
        const pairs = schedulePairs[day];
        if(pairs.length === 0) continue;
        pairs.forEach(pair => {
          const div = document.createElement('div');
          div.classList.add('schedule-item', 'glass-tile');

          const dayName = weekdayName(day);
          const startStr = pair.start ? formatTime(pair.start.hour, pair.start.minute) : '?';
          const endStr = pair.end ? formatTime(pair.end.hour, pair.end.minute) : '?';

      div.innerHTML = `
  <span>${dayName}: <span class="light-hours">${startStr} - ${endStr}</span></span>
  <button class="btn btn-sm btn-remove" data-start-id="${pair.start.id}" data-end-id="${pair.end ? pair.end.id : ''}">
    <i class="bi bi-trash"></i>
  </button>
`;


          scheduleItemsContainer.appendChild(div);
        });
      }

      // Dodaj event listener do przycisków usuwania
      document.querySelectorAll('.btn-remove').forEach(btn => {
        btn.onclick = async () => {
          if (!confirm('Na pewno usunąć ten wpis?')) return;

          const startId = btn.getAttribute('data-start-id');
          const endId = btn.getAttribute('data-end-id');

          try {
            if (startId) {
              await fetch(`${supabaseUrl}/harmonogram?id=eq.${startId}`, {
                method: 'DELETE',
                headers: {
                  apikey: apiKey,
                  Authorization: `Bearer ${apiKey}`
                }
              });
            }
            if (endId) {
              await fetch(`${supabaseUrl}/harmonogram?id=eq.${endId}`, {
                method: 'DELETE',
                headers: {
                  apikey: apiKey,
                  Authorization: `Bearer ${apiKey}`
                }
              });
            }
            //alert('Wpis usunięty');
            await fetchSchedule();
          } catch (err) {
            alert('Błąd podczas usuwania');
            console.error(err);
          }
        };
      });

    } catch (e) {
      scheduleItemsContainer.innerHTML = 'Błąd pobierania harmonogramu';
      console.error(e);
    }
  }

  // Inicjalizacja
  async function init() {
    await fetchValveState();
    await fetchSensorData();
    await fetchSchedule();
    updateButton();

    // Co 10s aktualizuj dane
    setInterval(() => {
      fetchValveState();
      fetchSensorData();
      fetchSchedule();
    }, 10000);
  }

  init();


const themeToggleBtn = document.getElementById('themeToggle');
const themeIcon = document.getElementById('themeIcon');

// Inicjalizacja motywu z localStorage
function applyThemeFromStorage() {
  const savedTheme = localStorage.getItem('theme');
  const themeIcon = document.getElementById('themeIcon');

  if (savedTheme === 'light') {
    document.body.classList.add('light-mode');
    if (themeIcon) {
      themeIcon.classList.remove('bi-moon');
      themeIcon.classList.add('bi-sun');
    }
  } else {
    document.body.classList.remove('light-mode');
    if (themeIcon) {
      themeIcon.classList.remove('bi-sun');
      themeIcon.classList.add('bi-moon');
    }
  }
}


// Przełącznik motywu
if (themeToggleBtn && themeIcon) {
  themeToggleBtn.addEventListener('click', () => {
    const isLight = document.body.classList.toggle('light-mode');
    localStorage.setItem('theme', isLight ? 'light' : 'dark');
    themeIcon.className = isLight ? 'bi bi-sun fs-4' : 'bi bi-moon fs-4';
  });
}
// Ustaw motyw przy starcie
applyThemeFromStorage();










// Referencja do modala bootstrapowego i ctx wykresu
const chartModal = new bootstrap.Modal(document.getElementById('chartModal'));
const ctx = document.getElementById('sensorChart').getContext('2d');
let sensorChart = null;

function lightenColor(color, percent) {
  const rgb = color.match(/\d+/g).map(Number);
  const newRgb = rgb.map(c => Math.min(255, Math.floor(c + (255 - c) * percent)));
  return `rgb(${newRgb.join(',')})`;
}

// Funkcja do pobrania ostatnich 2880 rekordów i wyświetlenia wykresu
async function showChart(type) {
  let label, borderColor, backgroundColor, yAxisLabel;

  if (type === 'temperatura') {
    label = 'Temperatura [°C]';
    borderColor = 'rgb(255, 99, 132)';
    backgroundColor = 'rgb(255, 0, 55)';
    yAxisLabel = 'Temperatura °C';
  } else if (type === 'wilgotnosc') {
    label = 'Wilgotność [%]';
    borderColor = 'rgb(54, 162, 235)';
    backgroundColor = 'rgb(0, 153, 255)';
    yAxisLabel = 'Wilgotność %';
  } else if (type === 'wilgotnosc_gleby') {
    label = 'Wilgotność gleby [%]';
    borderColor = 'rgb(75, 192, 192)';
    backgroundColor = 'rgb(0, 255, 255)';
    yAxisLabel = 'Wilgotność gleby %';
  } else {
    alert("Nieznany typ wykresu");
    return;
  }

  document.getElementById('chartModalLabel').textContent = `${label}`;

  async function fetchAllData() {
    const batchSize = 1000;
    let allData = [];
    let lastTimestamp = null;
    let hasMore = true;

    while (hasMore && allData.length < 2880) {
      let queryUrl = `${supabaseUrl}/czujniki?select=data_czas,temperatura,wilgotnosc,wilgotnosc_gleby&order=data_czas.desc&limit=${batchSize}`;
      if (lastTimestamp) {
        queryUrl += `&data_czas=lt.${encodeURIComponent(lastTimestamp)}`;
      }

      const res = await fetch(queryUrl, {
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`
        }
      });

      const data = await res.json();

      if (!data || data.length === 0) {
        hasMore = false;
      } else {
        allData = allData.concat(data);
        lastTimestamp = data[data.length - 1].data_czas;
        if (data.length < batchSize) {
          hasMore = false;
        }
      }
    }

    return allData.slice(0, 2880); // maks. 2880 rekordów
  }

  try {
    const data = await fetchAllData();

    if (!data || data.length === 0) {
      alert("Brak danych do wyświetlenia wykresu");
      return;
    }

    const reversedData = data.reverse(); // od najstarszych

    // Grupowanie po godzinie
    const hourlyData = {};
    for (const item of reversedData) {
      const date = new Date(item.data_czas);
      const hourKey = date.toISOString().substring(0, 13); // YYYY-MM-DDTHH
      if (!hourlyData[hourKey]) {
        hourlyData[hourKey] = [];
      }
      hourlyData[hourKey].push(item[type]);
    }

    const labels = [];
    const recentValues = [];
    const olderValues = [];

    const now = new Date();
    const cutoffTime = new Date(now.getTime() - 24 * 60 * 60 * 1000); // 24h temu

    for (const hourKey in hourlyData) {
      const hourValues = hourlyData[hourKey];
      const avg = hourValues.reduce((sum, val) => sum + val, 0) / hourValues.length;
      const dateObj = new Date(hourKey + ':00:00Z');

      const weekdayShort = dateObj.toLocaleString('pl-PL', { weekday: 'short' });
      const hourFormatted = dateObj.toLocaleTimeString('pl-PL', { hour: '2-digit', minute: '2-digit' });
      const localLabel = `${weekdayShort} godz. ${hourFormatted}`;

      labels.push(localLabel);

      if (dateObj >= cutoffTime) {
        olderValues.push(null);
        recentValues.push(Number(avg.toFixed(1)));
      } else {
        olderValues.push(Number(avg.toFixed(1)));
        recentValues.push(null);
      }
    }

    if (sensorChart) sensorChart.destroy();

    sensorChart = new Chart(ctx, {
      type: 'bar',
      data: {
        labels: labels,
        datasets: [
          {
            label: `${label} (24–48h temu)`,
            data: olderValues,
            borderColor: borderColor,
            backgroundColor: backgroundColor,
            borderRadius: 6,
          },
          {
            label: `${label} (ostatnie 24h)`,
            data: recentValues,
            borderColor: borderColor,
            backgroundColor: lightenColor(backgroundColor, 0.5),
            borderRadius: 6,
          }
        ]
      },
      options: {
        responsive: true,
        scales: {
          x: {
            display: true,
            title: { display: true, text: 'Dzień i godzina' }
          },
          y: {
            display: true,
            title: { display: false, text: yAxisLabel }
          }
        },
        plugins: {
          legend: { display: false }
        }
      }
    }); 

fetchChartTileData(type);

    chartModal.show();
    

  } catch (err) {
    alert('Błąd pobierania danych do wykresu');
    console.error(err);
  }
}





// Dodaj eventy kliknięcia na kafelki
tempTile.parentElement.addEventListener('click', () => showChart('temperatura'));
humTile.parentElement.addEventListener('click', () => showChart('wilgotnosc'));
glebaTile.parentElement.addEventListener('click', () => showChart('wilgotnosc_gleby'));



const scheduleBtn = document.getElementById('scheduleBtn');
const scheduleModalElement = document.getElementById('scheduleModal');

if (scheduleBtn && scheduleModalElement) {
  const scheduleModal = new bootstrap.Modal(scheduleModalElement);

  scheduleBtn.addEventListener('click', () => {
    scheduleModal.show();
  });
}


  // Otwieranie modala informacji po kliknięciu przycisku "Informacje"
const infoModal = new bootstrap.Modal(document.getElementById('infoModal'));
const settingsBtn = document.getElementById('settingsBtn');

if (settingsBtn) {
  settingsBtn.addEventListener('click', () => {
    infoModal.show();
  });
}

 const wateringModal = new bootstrap.Modal(document.getElementById('wateringModal'), {
  backdrop: 'static',
  keyboard: false
});
const wateringTimerElem = document.getElementById('wateringTimer');
const closeWateringModalBtn = document.getElementById('closeWateringModalBtn');

let wateringStartTime = null;  // znacznik czasu rozpoczęcia podlewania (w ms)
let wateringInterval = null;

// Funkcja formatowania sekund na mm:ss
function formatSeconds(seconds) {
  const mins = Math.floor(seconds / 60).toString().padStart(2, '0');
  const secs = (seconds % 60).toString().padStart(2, '0');
  return `${mins}:${secs}`;
}

// Uruchom timer
function startWateringTimer() {
  if (!wateringStartTime) wateringStartTime = Date.now();

  // Aktualizuj timer natychmiast
  updateWateringTimer();

  wateringInterval = setInterval(updateWateringTimer, 1000);
}

// Aktualizacja wyświetlanego timera
function updateWateringTimer() {
  const now = Date.now();
  const elapsedSeconds = Math.floor((now - wateringStartTime) / 1000);
  wateringTimerElem.textContent = formatSeconds(elapsedSeconds);
}

// Zatrzymaj timer i schowaj modal
function stopWateringTimer() {
  wateringStartTime = null;
  clearInterval(wateringInterval);
  wateringInterval = null;
  wateringModal.hide();
}

// Zmodyfikuj toggleValve by wywoływać pokazywanie i ukrywanie modala
async function toggleValve() {
  valveBtn.disabled = true;
  valveBtn.textContent = 'Aktualizacja...';

  const newState = !currentState;

  try {
    const res = await fetch(`${supabaseUrl}/status?id=eq.${recordId}`, {
      method: 'PATCH',
      headers: {
        apikey: apiKey,
        Authorization: `Bearer ${apiKey}`,
        'Content-Type': 'application/json'
      },
      body: JSON.stringify({ valve_state: newState })
    });

    if (!res.ok) throw new Error('Błąd zmiany stanu');
    currentState = newState;
    updateButton();

    // Jeśli włączamy podlewanie - pokaz timer
    if (currentState) {
      wateringStartTime = Date.now();
      wateringModal.show();
      startWateringTimer();
    } else {
      // wyłączamy podlewanie - ukryj timer
      stopWateringTimer();
    }

  } catch (e) {
    alert("Nie udało się zmienić stanu zaworu");
    console.error(e);
    updateButton();
  }
}

// Obsługa przycisku anulowania podlewania w modalu (opcjonalnie możesz powiązać z wyłączaniem zaworu)
closeWateringModalBtn.addEventListener('click', async () => {
  // Wyłącz podlewanie klikając przycisk, czyli wywołaj toggle jeśli podlewanie jest włączone
  if (currentState) {
    await toggleValve();
  }
});
 
</script>

<script>
  // Pobieranie historii podlewania
  async function fetchHistoryData() {
    try {
      const res = await fetch(`${supabaseUrl}/historia?select=id,status,czas&order=czas.desc&limit=50`, {
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`
        }
      });

      const data = await res.json();
      const list = document.getElementById('historyList');
      list.innerHTML = '';

      if (data.length === 0) {
        const li = document.createElement('li');
        li.className = 'list-group-item bg-dark text-white border-secondary small';
        li.textContent = 'Brak danych w historii.';
        list.appendChild(li);
        return;
      }

      data.forEach(entry => {
        const li = document.createElement('li');
        li.className = 'list-group-item d-flex justify-content-between align-items-center border-0 py-2 px-2';

        const isOn = entry.status === true || entry.status === "TRUE";
        const statusText = isOn ? "Włączono podlewanie" : "Wyłączono podlewanie";
        const badgeClass = isOn ? 'bg-primary' : 'bg-danger';

        const dateObj = new Date(entry.czas);
        const dataCzas = dateObj.toLocaleDateString('pl-PL');
        const godzina = dateObj.toLocaleTimeString('pl-PL', { hour: '2-digit', minute: '2-digit' });

        li.innerHTML = `
          <span class="badge ${badgeClass}  px-2 py-1 rounded-pill fw-normal small">${statusText}</span>
          <span class="text-50 small"><strong>${godzina}</strong>, ${dataCzas}</span>
        `;

        list.appendChild(li);
      });

    } catch (e) {
      console.error("Błąd podczas pobierania historii:", e);
      const list = document.getElementById('historyList');
      list.innerHTML = '<li class="list-group-item border-secondary small">Błąd pobierania danych.</li>';
    }
  }

  // Obsługa przycisku otwierającego modal historii
  document.getElementById('historyBtn').addEventListener('click', () => {
    fetchHistoryData().then(() => {
      const modal = new bootstrap.Modal(document.getElementById('historyModal'));
      modal.show();
    });
  });
</script>

<script>
  async function initCalendarDots() {
    try {
      const res = await fetch(`${supabaseUrl}/historia?select=czas,status&order=czas.desc&limit=1000`, {
        headers: {
          apikey: apiKey,
          Authorization: `Bearer ${apiKey}`
        }
      });

      const data = await res.json();

      const daysWithWatering = new Set();

      // Funkcja konwertująca na lokalny YYYY-MM-DD
      const toLocalYMD = (dateObj) => {
        return dateObj.getFullYear() + '-' +
               String(dateObj.getMonth() + 1).padStart(2, '0') + '-' +
               String(dateObj.getDate()).padStart(2, '0');
      };

      data.forEach(entry => {
        if (entry.status === true || entry.status === "TRUE") {
          const d = new Date(entry.czas);
          daysWithWatering.add(toLocalYMD(d));
        }
      });

      flatpickr("#historyCalendar", {
        inline: true,
        locale: "pl",
        static: true,
        disableMobile: true,
        onDayCreate: function(dObj, dStr, fp, dayElem) {
          const date = toLocalYMD(dayElem.dateObj);

          if (daysWithWatering.has(date)) {
            // Usuwamy poprzednie kropki, jeśli były:
            const oldDot = dayElem.querySelector(".calendar-dot");
            if (oldDot) oldDot.remove();

            // Dodajemy klasę, by cały dzień był niebieskim kółkiem:
            dayElem.classList.add("watering-day");
          }
        }
      });

    } catch (err) {
      console.error("Błąd pobierania danych do kalendarza:", err);
    }
  }

  document.getElementById('historyBtn').addEventListener('click', () => {
    initCalendarDots();
  });
</script>


</div>

<script>
const API_KEY = "7594c17748bbb605ca342ede04a94109";


async function loadWeather() {
  try {

       // Odczytujemy współrzędne z localStorage
    const lat = localStorage.getItem("weatherLat") || 50.90;
    const lon = localStorage.getItem("weatherLon") || 16.50;


    console.log("⏳ Pobieranie danych pogodowych...");

    // 🟦 1. Pobierz prognozę 5-dniową
    const forecastRes = await fetch(`https://api.openweathermap.org/data/2.5/forecast?lat=${lat}&lon=${lon}&units=metric&lang=pl&appid=${API_KEY}`);
    if (!forecastRes.ok) throw new Error("Błąd prognozy: " + forecastRes.status);
    const forecastData = await forecastRes.json();

    // 🟦 2. Pobierz aktualną pogodę
    const currentRes = await fetch(`https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&units=metric&lang=pl&appid=${API_KEY}`);
    if (!currentRes.ok) throw new Error("Błąd pogody bieżącej: " + currentRes.status);
    const currentData = await currentRes.json();

    // 🟩 AKTUALNA POGODA
    const currentTempWeather = Math.round(currentData.main.temp);
    const currentIcon = currentData.weather[0].icon;
    //const currentDesc = currentData.weather[0].description;

    document.getElementById("currentTempWeather").textContent = `${currentTempWeather}°C`;
    document.getElementById("currentIcon").src = `https://openweathermap.org/img/wn/${currentIcon}.png`;
    //document.getElementById("currentDesc").textContent = currentDesc;

    // 🟩 PROGNOZA NA KOLEJNE DNI (godz. 14:00)
    const container = document.querySelector(".weather-forecast");
    if (!container) return console.error("❌ Brak kontenera .weather-forecast");

    container.innerHTML = "";
    const days = ['Nd','Pn','Wt','Śr','Cz','Pt','Sb'];
    const shownDates = new Set();

    forecastData.list.forEach(item => {
      const date = new Date(item.dt * 1000);
      const hours = date.getHours();
      const day = date.getDay();
      const dateStr = date.toDateString();

      if (hours === 14 && !shownDates.has(dateStr)) {
        shownDates.add(dateStr);
        const icon = item.weather[0].icon;
        const temp = Math.round(item.main.temp);

        const div = document.createElement("div");
        div.className = "glass-weather text-center p-2";
        div.style.minWidth = "40px";
        div.innerHTML = `
          <div class="fw-bold">${days[day]}</div>
          <img src="https://openweathermap.org/img/wn/${icon}.png" alt="">
          <div>${temp}°C</div>
        `;
        container.appendChild(div);
      }
    });

    console.log("✅ Pogoda aktualna i prognoza załadowana");
  } catch (e) {
    console.error("❌ Błąd ładowania pogody:", e);
  }
}

document.addEventListener("DOMContentLoaded", loadWeather);
</script>


<script>
 let mapModal;
let selectedLat = localStorage.getItem("weatherLat") || 50.90;  // Odczytujemy z localStorage, jeśli brak - domyślnie 50.90
let selectedLon = localStorage.getItem("weatherLon") || 16.50;  // Odczytujemy z localStorage, jeśli brak - domyślnie 16.50

function initMap() {
  // Inicjalizowanie mapy
  mapModal = L.map('mapModal', {
    center: [selectedLat, selectedLon],
    zoom: 13
  });

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png').addTo(mapModal);

  // Dodanie znacznika
  const marker = L.marker([selectedLat, selectedLon]).addTo(mapModal);

  // Funkcja wywoływana po kliknięciu na mapie
  mapModal.on('click', function (e) {
    selectedLat = e.latlng.lat;
    selectedLon = e.latlng.lng;
    marker.setLatLng(e.latlng);  // Przesunięcie znacznika
  });
}

$('#modalMap').on('shown.bs.modal', function () {
  // Inicjalizowanie mapy po otwarciu modala
  setTimeout(initMap, 300);
});

document.getElementById("saveLocation").addEventListener("click", function () {
  // Zapisanie współrzędnych do localStorage
  localStorage.setItem("weatherLat", selectedLat);
  localStorage.setItem("weatherLon", selectedLon);

  // Zamknięcie modala
  $('#modalMap').modal('hide');

  // Załadowanie nowych danych pogodowych
  loadWeather();
});

</script>




</body>
</html>
