document.querySelectorAll('.food-card').forEach(card => {
    card.addEventListener('click', function() {
        const query = this.querySelector('p').innerText;
        document.getElementById('search-query').value = `nutrition of ${query.toLowerCase()}`;
    });
});
