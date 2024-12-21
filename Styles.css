// Vieritys osioihin
function scrollToSection(sectionId) {
  const section = document.getElementById(sectionId);
  section.scrollIntoView({ behavior: 'smooth' });
}

// Lomakkeen validointi ja viestin lähetys
const form = document.getElementById('contactForm');
form.addEventListener('submit', function (e) {
  e.preventDefault();

  const name = document.getElementById('name').value;
  const email = document.getElementById('email').value;
  const message = document.getElementById('message').value;

  if (name && email && message) {
    document.getElementById('formMessage').innerText =
      'Kiitos viestistäsi, otamme pian yhteyttä!';
    form.reset();
  } else {
    document.getElementById('formMessage').innerText =
      'Täytä kaikki kentät!';
  }
});
