<style>
body {
    color: #333;
    font-family: "Noto Sans",sans-serif;
    font-size: 1em;
    line-height: 1.8em;
}
h1 {
    font-family: "Montserrat",sans-serif;
    font-weight: 400;
    line-height: 1.5em;
    margin: 2.5rem 0 .9375rem 0;
}

.callout {
    border: 2px solid #efefef;
    background-color: #f9f9f9;
    padding: .9375rem 1.25rem .625rem 1.25rem;
    margin: 0 0 1.25rem 0;
}
.callout--info {
    background-color: #f2f8ff;
    border-color: #deedff;
}
</style>
##Magnetic Force on a Particle
- The strength of the magnetic force on a charged particle follows the formula
\\[\overrightarrow F_M=q(\overrightarrow v \times \overrightarrow B)\\]
where $$\overrightarrow F_M$$ is the magnetic force vector, $$q$$ is the particle's charge, $$\overrightarrow v$$ is the particle's velocity vector, and $$\overrightarrow B)$$ is the magnetic field vector.
<div class="callout callout--info">
Note the cross product. $$\overrightarrow v \times \overrightarrow B$$ is equal to $$vB\sin\theta$$. This means that if a particle moves parallel to the magnetic field, the magnetic force will be $$0$$. The direction of the force vector is determined by the right hand rule, so the magnetic force will always act perpendicular to the particle's velocity.
</div>
- In a uniform magnetic field, the magnetic force acts like a centripetal force, causing charged particles to move in a circular path. You will often need to set the centripetal force ($$F_C=\frac{mv^2}r$$) equal to $$F_M$$ and solve for one of the variables: $$\frac{mv^2}r=qvB$$, therefore $$\frac{mv}r=qB$$

##Magnetic Force on a Current-Carrying Wire
- The magnetic force on a current-carrying wire follows the formula
\\[\overrightarrow F_M=\int I(\overrightarrow{dl}\times \overrightarrow  B)\\]
where $$I$$ is the current in the wire, $$dl$$ represents integration over the wire's length, and $$\overrightarrow B$$ is the external magnetic field.
(Example here)
- For a loop of wire, the net magnetic force will be zero, but there may be a net torque.

##Magnetic Fields Created by Current-Carrying Wires
- The magnetic field created by a long, straight current-carrying wire follows the formula:
\\[B=\frac{\mu_0 I}{2\pi r}\\]
where $$\mu_0$$ is a constant called the vacuum permeability, $$I$$ is the current in the wire, and $$r$$ is the distance from the wire.
- The magnetic field curls around the wire following the right hand rule if your thumb points in the direction of the conventional current.
- Principle of superposition: If you have multiple wires, calculate $$\overrightarrow B$$ for each one, then add all the $$\overrightarrow B$$ vectors together.
- A solenoid is a wire coiled many times in a spiral shape. The magnetic field inside a solenoid follows the equation
\\[B=\mu_o nI\\]
where n is the number of coils.

##Biot-Savart Law
- The Biot-Savart law describes the magnetic field at a point near a current-carrying wire.
\\[d\overrightarrow B=\frac{\mu_o}{4\pi}\frac{I(d\overrightarrow l\times \widehat r)}{r^2}\\]
Breaking this down: $$\mu_0$$ is the vacuum permeability, $$I$$ is current, and $$r$$ is distance of this point from the wire. $$d\overrightarrow l$$ represents an infinitesimal length of the wire, and $$d\overrightarrow B$$ represents the amount of magnetic field that that length of wire contributes to the total value of $$B$$. By taking the interal of each side, you can find the total magnetic field at the point. $$\widehat r$$ is the unit vector (it has a magnitude of 1) which specifies the direction from the current to the point you are measuring.
- AP might have you use this rule to calculate the magnetic field along the axis of a circular loop of current. (Insert example here)

##Ampere's Law
- Ampere's law for magnetism is similar to Gauss's law for electrostatics. It states that if you draw an imaginary loop (called an Amperian loop) around a current-carrying wire, and integrate the magnetic field over that loop, the value will be equal to the vacuum permeability times the current enclosed in the loop:
\\[\oint\overrightarrow B\cdot d\overrightarrow l=\mu_0 I\\]
- In AP, $$\overrightarrow B$$ will always be constant, and your amperian loop will usually be a circle. In this case, the formula becomes:
\\[\overrightarrow B2\pi r=\mu_0 I\\]
This is where the formula for the field generated by a long, current carrying wire originates from.