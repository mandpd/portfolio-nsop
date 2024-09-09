## Overview

Jointly Developed a set of Network Standard Operating Procedures best practices for a client's network operations. This encompassed Alcatel Lucent Enterprise (ALE) switches and routers, Palo Alto Network (PAN) firewalls, Hewlett Packard Enterprice (HPE) Aruba Wireless Networks equipment, and Statseeker network monitoring software.

## Exhibited Skills

- Network expertise in switching, routing. security, and wireless networking.
- Documentation and technical writing skills.
- Collaboration and teamwork.
- Coding knowledge of `mkdocs` document generation, and `markdown`.

## Details

As chief engineer on a large infrastructure deployment program for a client, I was tasked with developing a set of Network Standard Operating Procedures (SOPs) for the client's network operations team. The SOPs were to be used as a reference guide for the client's network operations teams to follow when managing the network infrastructure. I worked with the vendor SMEs to develop best practice task lists for each of the vendor hardware and software components. Apropriate command line interactions were included as code snippets and image captures of corresponding terminal outputs were also added. We generated daily, weekly, and monthly checklists that referenced specific tasks in the overall vendor task lists. I converted into a `mkdocs` site for easy access and reference.

### Switch Routing Example Page

This is an example of a page for the ALE switches specific to ARP tables.

<div style="text-align: center;">
    <img src="./images/alcatel-lucent.png" alt="Alcatel Lucent" width="500" onclick="openModal('./images/alcatel-lucent.png')" style="cursor: pointer;"/>
</div>

### Firewall Security Example Page

This is an example of a page for the PAN firewalls checking an aspect of the environmental status of a firewall.

<div style="text-align: center;">
    <img src="./images/palo-alto.png" alt="Palo Alto" width="500" onclick="openModal('./images/palo-alto.png')" style="cursor: pointer;"/>
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
