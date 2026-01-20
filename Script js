function orderNow() {
    let phone = "919XXXXXXXXX"; // apna number
    let text = "Hello! I want to order fresh dairy products.";
    let url = "https://wa.me/" + phone + "?text=" + encodeURIComponent(text);
    window.open(url, "_blank");
}

function validateForm() {
    let name = document.getElementById("name").value;
    let phone = document.getElementById("phone").value;
    let message = document.getElementById("message").value;
    let error = document.getElementById("error");

    if (name === "" || phone === "" || message === "") {
        error.innerText = "⚠️ Please fill all fields";
        return false;
    }

    if (phone.length < 10) {
        error.innerText = "⚠️ Enter valid mobile number";
        return false;
    }

    alert("Message submitted successfully (Demo)");
    return true;
}
