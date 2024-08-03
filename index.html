const age_dialog = document.getElementById('age');
const users_name = document.getElementById('users_name');
const profile_pic = document.getElementById('pfp');
const no_profile_pic = document.getElementById('nopfp');
const titlle = document.getElementById('title');
const stylesheet = document.getElementById('stylesheet');
const input_text = document.getElementById('input_text');
const input = document.getElementById('input');
const welcome_dialo = document.getElementById('welcome_dialog');
const updates = document.getElementById('updates');

let age_count = 13;
let required_age = 13;

appOnStart();

const my_age = document.createElement('h1');
const younger = document.createElement('button');
const min_age = document.createElement('button');
const older = document.createElement('button');
const age_buttons = document.createElement('div');
const age_description = document.createElement('h2');

my_age.id = 'my_age';
my_age.textContent = age_count;
younger.textContent = '-';
older.textContent = '+';
min_age.textContent = 'Done';
younger.id = 'younger';
min_age.id = 'min_age';
younger.className = 'age_button';
min_age.className = 'age_button';
older.className = 'age_button';
age_buttons.id = 'age_buttons';
age_buttons.className = 'age_buttons';
age_description.textContent = 'How old are you ?'
age_description.id = 'age_description';

age_dialog.prepend(my_age);
age_buttons.prepend(older);
age_buttons.prepend(min_age);
age_buttons.insertBefore(younger, min_age)
age_dialog.append(age_buttons);
age_dialog.prepend(age_description)

older.onclick = function () {
    age_count++;
    my_age.textContent = age_count;
    my_age.style.color = '#fff';
    if (age_count >= 13) {
        age_description.textContent = 'Click Done to confirm !';
    }
    else {
        my_age.style.color = 'red';
        age_description.textContent = 'You are under age !';
    }
}
younger.onclick = function () {
    age_count--;
    my_age.textContent = age_count;
    my_age.style.color = '#fff';
    if (age_count < 13) {
        age_description.textContent = 'You are under age !';
        my_age.style.color = 'red';
    }
}
min_age.onclick = function () {
    if (age_count >= 13) {
        my_age.style.color = 'rgb(14, 243, 26)';
        age_dialog.style.display = 'none'; 3000();
    }
    else {
        age_description.textContent = 'You need to be atleast ' + (required_age - age_count) + ' years older to join us ';
    }
}

let username = 'me_srek';
username = username.toLowerCase();
username = username.padEnd(5, '.')
if (username.startsWith(' ')) {
    username = username.trim();
}
if (username.endsWith(' ')) {
    username = username.trim();
}
if (username.includes(' ')) {
    username = username.replaceAll(' ', '');
}

function appOnStart() {
    app_data = 'app.json';
    settings_data = 'settings.json';
    fetch(app_data)
        .then((response) => response.json())
        .then((data) => {
            users_name.textContent = data.user.name;
            updates.innerHTML = '<img id="itemimg" src="Assets/IMG_20240206_205525_636.jpg" alt=""> <p id="updatestxt">' + data.updates.notify_title + '</p>';
            updates.addEventListener('click', function () {
                window.open(data.updates.url);
            });
            if (data.user.pfp.includes('.' & '/')) {
                profile_pic.src = data.user.pfp;
                no_profile_pic.style.display = 'none';
                profile_pic.style.display = 'block';
            }
            else {
                no_profile_pic.textContent = data.user.name.slice(0, 1);
                no_profile_pic.style.display = 'block';
                profile_pic.style.display = 'nonr';
            }
            if (data.user.name == '') {
                input_text.textContent = 'Enter name';
                users_name.textContent = 'New User';
                input.addEventListener('keydown', function(event) {
                    if (event.key === 'Enter') {
                        // function when enter is clicked
                }
                });
            }
            else if (data.user.username == '') {
                input_text.textContent = 'Create a username';
            }
            else if (data.user.id == '') {
                const p = 3;
                const min_id = 10000;
                const max_id = 99999;
                const my_id = Math.floor(Math.random() * (max_id - min_id + 1));
                input_text.textContent = 'Your id:' + my_id;
                input.disabled = true;
            }
            else {
                input_text.textContent = 'Welcome  ' + data.user.name;
                welcome_dialo.style.display = 'none';
            }
            title.textContent = data.app.title;
            stylesheet.href = data.app.stylesheet;
        });
    function applySettings() {
        fetch(settings_data)
            .then((response) => response.json())
            .then((data) => {
                if (data.app.theme.light == true) {
                    console.log('light mode on');
                }
                else if (data.app.theme.dark == true) {
                    console.log('dark mode on');
                }
                if (data.user.age >= 13) {
                    age_dialog.style.display = "none";
                }
                else {
                    age_dialog.style.display = "block";
                }
            });
    }
    applySettings();
    userinfo();
};

