<template>
    <div class="contact" id="contact">
        <h1 class="title contact__title">Contact</h1>
        <div class="contact__columns">
            <div class="contact__form">
                <div class="contact__flex-container">
                    <div>
                        <label for="name" class="contact__form-label">Your name</label>
                        <input type="text" id="name" name="name" class="contact__form-field" />
                    </div>
                    <div>
                        <label for="email" class="contact__form-label">Your E-Mail</label>
                        <input type="text" id="email" name="email" class="contact__form-field" />
                    </div>
                </div>
                <label for="message" class="contact__form-label">Message</label>
                <textarea type="text" id="message" name="message" class="contact__form-field contact__form-textarea"/>
                <button class="contact__form-send">Send</button>
            </div>
            <div class="contact__text">
                <p class="contact__label">Have an idea for a project? Just looking to explore and see the possibilities? I'm here to help.</p>
                <p class="contact__name">Postma Elena</p>
                <div class="contact__socials">
                    <a href="https://facebook.com" class="contact__facebook">f</a>
                    <a href="https://linkedin.com"  class="contact__linkedin">in</a>
                </div>
                <a href="mailto:postma.elena@gmail.co" class="contact__email">e-mail: postma.elena@gmail.co</a>
            </div>
        </div>
    </div>
</template>
