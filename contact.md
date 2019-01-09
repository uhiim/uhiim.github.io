---
layout: static
title: Contact
description: If there is anything you want to ask about the post (manga - manhua - manhwa). <br/> Please complete the form below.
---
<div class="row">
    <form class="col s12">
        <div class="row">
            <div class="input-field col s6">
                <input id="full_name" type="text" class="validate">
                <label for="full_name">Full Name</label>
            </div>
            <div class="input-field col s6">
                <input id="title" type="text" class="validate">
                <label for="title">Title</label>
            </div>
        </div>
        <div class="row">
            <div class="input-field col s12">
                <input id="email" type="email" class="validate">
                <label for="email">Email</label>
            </div>
        </div>
        <div class="row">
            <div class="input-field col s12">
                <i class="material-icons prefix">mode_edit</i>
                <textarea id="msg" class="materialize-textarea"></textarea>
                <label for="msg">Message</label>
            </div>
        </div>
        <div class="row">
            <div class="input-field col s6">
                <input name="group1" type="radio" id="criticism" />
                <label for="criticism">Criticism</label>
                <input name="group1" type="radio" id="suggestion" />
                <label for="suggestion">Suggestion</label>
            </div>
            <div class="input-field col s6">
                <select>
                    <option value="" disabled selected>Choose your option</option>
                    <option value="1">Manga</option>
                    <option value="2">Manhua</option>
                    <option value="3">Manhwa</option>
                </select>
                <label>Type Select</label>
            </div>
        </div>
        <div class="row">
            <div class="col s12">
                <button class="btn waves-effect waves-light" type="submit" name="send" value="form">Submit
                    <i class="material-icons right">send</i>
                </button>
            </div>
        </div>
    </form>
</div>