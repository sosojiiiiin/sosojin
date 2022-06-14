# sosojin
body {
    max-width: 900px;
    width: 100%;
    margin: 0 auto;
}
img {
    width: 100%;
    height: 100%;
    display: block;
}
.input_img {
    position: relative;
}

.input_name {
    width: 65%;
    position: absolute;
    top: 32%;
    left: 150px;
}
.input_phone {
    width: 65%;
    position: absolute;
    top: 50%;
    left: 150px;
}
.submit_btn {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 30%;
    cursor: pointer;
}
.input_name input {
    font-size: 20px;
    width: 100%;
    padding: 5px 5px;
}

.input_phone input {
    font-size: 20px;
    width: 100%;
    padding: 5px 5px;
}

.label {
    color: white;
    font-size: 20px;
    margin-bottom: 10px;
}

@media (max-width: 820px) {
    .input_name {
        width: 65%;
        position: absolute;
        top: 32%;
        left: 120px;
    }
    .input_phone {
        width: 65%;
        position: absolute;
        top: 50%;
        left: 120px;
    }
    .label {
        color: white;
        font-size: 20px;
        margin-bottom: 5px;
    }
}

@media (max-width: 700px) {
    .input_name {
        width: 65%;
        position: absolute;
        top: 30%;
        left: 90px;
    }
    .input_phone {
        width: 65%;
        position: absolute;
        top: 50%;
        left: 90px;
    }

    .input_name input {
        font-size: 15px;
        width: 100%;
        padding: 5px 5px;
    }

    .input_phone input {
        font-size: 15px;
        width: 100%;
        padding: 5px 5px;
    }

    .label {
        color: white;
        font-size: 15px;
        margin-bottom: 5px;
    }
}

@media (max-width: 450px) {
    .input_name {
        width: 65%;
        position: absolute;
        top: 30%;
        left: 60px;
    }
    .input_phone {
        width: 65%;
        position: absolute;
        top: 50%;
        left: 60px;
    }

    .input_name input {
        font-size: 10px;
        width: 100%;
        padding: 5px 5px;
    }

    .input_phone input {
        font-size: 10px;
        width: 100%;
        padding: 5px 5px;
    }

    .label {
        color: white;
        font-size: 10px;
        margin-bottom: 3px;
    }
}
@media (max-width: 300px) {
    .input_name {
        width: 65%;
        position: absolute;
        top: 30%;
        left: 50px;
    }
    .input_phone {
        width: 65%;
        position: absolute;
        top: 50%;
        left: 50px;
    }
}
