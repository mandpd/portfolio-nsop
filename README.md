# Network Standard Operating Procedures - Best Practices

## Overview

Jointly Developed a set of Network Standard Operating Procedures best practices for a client's network operations. This encompassed Alcatel Lucent Enterprise (ALE) switches and routers, Palo Alto Network (PAN) firewalls, Hewlett Packard Enterprice (HPE) Aruba Wireless Networks equipment, and Statseeker network monitoring software.

## Exhibited Skills

- Network expertise in switching, routing. security, and wireless networking.
- Documentation and technical writing skills.
- Collaboration and teamwork.
- Coding knowledge of `mkdocs` document generation, and `markdown`.

## Details

Switch Routing Example Page

<div style="text-align: center;">
    <img src="./images/alcatel-lucent.png" alt="Alcatel Lucent" width="500" onclick="openModal('./images/alcatel-lucent.png')"/>
</div>

Firewall Security Example Page

<div style="text-align: center;">
    <img src="./images/palo-alto.png" alt="Palo Alto" width="500" onclick="openModal('./images/palo-alto.png')"/>
</div>

<!-- Modal Structure -->
<div id="myModal" class="modal">
    <span class="close" onclick="closeModal()">&times;</span>
    <img class="modal-content" id="modalImage">
</div>

<style>
.modal {
    display: none;
    position: fixed;
    z-index: 1;
    padding-top: 60px;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgb(0,0,0);
    background-color: rgba(0,0,0,0.9);
}

.modal-content {
    margin: auto;
    display: block;
    width: 80%;
    max-width: 700px;
}

.close {
    position: absolute;
    top: 15px;
    right: 35px;
    color: #f1f1f1;
    font-size: 40px;
    font-weight: bold;
    transition: 0.3s;
}

.close:hover,
.close:focus {
    color: #bbb;
    text-decoration: none;
    cursor: pointer;
}
</style>

<script>
function openModal(src) {
    var modal = document.getElementById("myModal");
    var modalImg = document.getElementById("modalImage");
    modal.style.display = "block";
    modalImg.src = src;
}

function closeModal() {
    var modal = document.getElementById("myModal");
    modal.style.display = "none";
}
</script>
