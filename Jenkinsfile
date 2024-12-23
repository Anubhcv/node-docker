pipeline {
    agent any
    stages{
        stage("checkout"){
            steps{
                checkout scm
            }
        }

        stage("Test"){
            steps{
                sh 'npm test'
            }
        }

        stage("Build"){
            steps{
                sh 'npm run build'
            }
        }
        stage("Build Image"){
            steps{
                sh 'docker build -t node-app:1.0 .'
            }
        
        }
        //  stage("Login to DockerHub") {
        //     steps {
        //         script {
        //             // Login to DockerHub
        //             def dockerhub_creds = credentials('docker-log')
        //             sh "echo ${dockerhub_creds.password} | docker login -u ${dockerhub_creds.username} --password-stdin"
        //         }
        //     }
        // }

        // stage("Push Image") {
        //     steps {
        //         sh 'docker push anubhcv/node-app:1.0'
        //     }
        // }

        
    }
}





Jeans instability : conditions under which a cloud of gas becomes gravitationally unstable and collapse to form a new object.

self gravity overcomes pressure force and the cloud collapses leads to a denser cloud, G becomes stronger, further collapse, new object forms

ISM gas between stars, interstellar medium

Type Ia supernova: occurs in binary systems, one of them is a white dwarf, the other one can be anything 

Characterized by very specific light curve, rapid rise in brightness then much slower decline over weeks after the explosion.

Standard candles because of the Phillip relative that connects the maximum B band magnitude to the dimming rate(known peak luminosity, very bright so the are visible at long distances)

Supernova remnants observed with radio telescopes because they emit synchrotron radiation(radiation produced by high energy electrons spiraling around magnetic field lines). The e!- are caused by shock waves that accelerate the particles.

Metallicity : amount of elements we have in comparison to H

Origins : exploding white dwarf, newton star merger, interaction of high energy cosmic rays with interstellar gas, accretion of intergalactic gavel metals are formed in the cave of stars as they evolve. 

Interstellar dust shows a temperature below the effective surface T at stars due to thermal radiation(causes radiation shift from blue to red - absorbs blue from stars, heats up, loses energy and reflects red).

Rayleigh scattering reddening of the star light passing through the dust



Page-2

Typical extinction curve, why extinction causes reddening?

Extinction curve indicates average absorption.
 Cross section !

Reddening occurs due to the light scattering of dust and other matter in the interstellar medium. Interstellar dust absorbs and scatters blue light waves more than red light waves, making stars appear redder than they are. Similar to the red sunset phenomenon, caused by dust particles in the atmosphere.

Page-3

Luminosity: amount of light emitted by an object

Standard candles: objects with known luminosity from their periodic properties ! Cepheids have a #pulsator period that's why we can calculate their absolute magnitude

Redshift:known from the lab

Effect caused by the doppler effect, as an object moves away from it redshift is observed as a displacement of spectral lines towards larger wavelengths 
z=0,1 : means the galaxy is moving away from us at 10% of C

Hubble law : the velocity at which a galaxy is moving is proportional to our distance from it

HII residues are formed when high energy radiation ionizes the surrounding gas

hot massive young star    emission of UV radiation     ionization of H2 from surrounding gas      free protons and electrons are formed

Ionized H gas emits light creating a spectrum at specific wavelengths corresponding to the transition between energy levels in the atoms. Mark prominent lines are a recombination and produce the Balmer series (

For OIII (double ionized oxygen 5000 ) basically the same process, ionization of gas produces ions such as O+2 and these ions produce emission lines 

Cooling time : time it takes for a gas to radiate away thermal energy

Hertz Russel diagram



page-4

Criterion to assign a spiral galaxy to a specific Hubble type

Ratio of the luminosity of the bulge compared to the disk(how bright is the central bulge compared to the central disk)

Amount of winding of the spiral arms(how tightly/loosely the spiral arms are)

Properties that systematically vary:
The arms in late type galaxies tend to be fragmented/knotty.
Early type (Sa) have prominent, bright central bulges and tightly wound arms. Sa~30%
Late type (Sc) have less prominent bulges and loosely wounded arms Sc~5%
Sa have smoothly distributed stars in their arms
(Arms are sites of ongoing start formation)
(Spiral galaxies are populated by stars that are average, much younger than the ones in elliptical galaxies)
Sa have older stars and vice versa
Inclination of the arms:
Sa~6

Freeman's law: almost all disk galaxies show the same central surface brightness 

