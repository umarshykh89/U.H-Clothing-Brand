```javascript
let cartCount = 0;

function addToCart() {

    cartCount++;

    document.getElementById("cart-count").textContent = cartCount;

    alert("Product added to your cart!");
}


function subscribe(event) {

    event.preventDefault();

    const email = document.getElementById("email").value;

    if (email) {
        alert("Thank you for joining the UH family!");
        document.getElementById("email").value = "";
    }
}