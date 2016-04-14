## Introduction

This extension provides an Post Processor for EXT:form to allow more powerful
e-mail delivery as the native one.

As this one extends the core Post Processor, every configuration also works for
this one. Just some more features are added.

## Usage

Currently the wizard is not supported, so you have to write the configuration
yourself. E.g.:

    postProcessor {
        1 = WebVision\WvFormEmail\Form\PostProcessor\Email
        1 {
        }
    }

The configuration will not be removed while using the wizard.
