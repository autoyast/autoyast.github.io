
## Minimal Profiles

The minimal profiles configure only the required minimal set of options,
the system defaults are used for everything else.

#### Minimal openSUSE Leap 15

File: [leap15.xml]({{ "/" | absolute_url }}mini/leap15.xml)  
Boot option: `autoyast={{ "/" | absolute_url }}mini/leap15.xml`

- Set `linux` password for the `root` user

File: [leap15_confirm.xml]({{ "/" | absolute_url }}mini/leap15_confirm.xml)  
Boot option: `autoyast={{ "/" | absolute_url }}mini/leap15_confirm.xml`

- Same as [leap15.xml]({{ "/" | absolute_url }}mini/leap15.xml)
- Additionally displays the installation summary, needs to be manually confirmed

#### Minimal SLES 15

Note: This profile assume the "Full" installation medium is used, if you
want to use the "Online" medium see the [registration](registration) examples.

File: [sles15.xml]({{ "/" | absolute_url }}mini/sles15.xml)  
Boot option: `autoyast={{ "/" | absolute_url }}mini/sles15.xml`

- Minimalistic configuration for Full installation medium
- Set `linux` password for the `root` user
- Adds the Basesystem module repository
- Selects SLES as the base product

File: [sles15_confirm.xml]({{ "/" | absolute_url }}mini/sles15_confirm.xml)  
Boot option: `autoyast={{ "/" | absolute_url }}mini/sles15_confirm.xml`

- Same as [sles15.xml]({{ "/" | absolute_url }}mini/sles15.xml)
- Additionally displays the installation summary, needs to be manually confirmed
