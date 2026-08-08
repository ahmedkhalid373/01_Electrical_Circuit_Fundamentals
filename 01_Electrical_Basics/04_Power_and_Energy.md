# Power and Energy

## Objective

Understand electrical power and energy and apply them to electrical
and power-electronic systems.

---

## 1. Electrical Power

Electrical power represents the **rate at which electrical energy is
transferred**.

$$
\boxed{P = VI}
$$

Where:

| Symbol | Meaning | Unit |
|---|---|---|
| $P$ | Power | W |
| $V$ | Voltage | V |
| $I$ | Current | A |

Therefore:

$$
1W = 1V \cdot 1A
$$

![Power and Energy](figures/5.Power_and_Energy.png)

---

## 2. Power in a Resistor

Starting from:

$$
P = VI
$$

Using Ohm's Law:

$$
V = IR
$$

we obtain:

$$
P = I^2R
$$

Alternatively:

$$
I = \frac{V}{R}
$$

Therefore:

$$
P = \frac{V^2}{R}
$$

The three equivalent forms are:

$$
\boxed{P = VI = I^2R = \frac{V^2}{R}}
$$

---

## 3. Choosing the Correct Formula

| Known quantities | Formula |
|---|---|
| $V$, $I$ | $P = VI$ |
| $I$, $R$ | $P = I^2R$ |
| $V$, $R$ | $P = \frac{V^2}{R}$ |

Choose the formula based on the quantities that are already known.

---

## 4. Worked Example — Power

A $10\Omega$ resistor is connected to a $20V$ source.

### Step 1 — Calculate current

$$
I = \frac{V}{R}
$$

$$
I = \frac{20}{10} = 2A
$$

### Step 2 — Calculate power

$$
P = VI
$$

$$
P = 20 \times 2
$$

$$
\boxed{P = 40W}
$$

The resistor dissipates **40 W** of electrical power.

---

## 5. Electrical Energy

Electrical energy represents the **total amount of energy transferred**.

For constant power:

$$
\boxed{E = Pt}
$$

Since:

$$
P = VI
$$

we can also write:

$$
\boxed{E = VIt}
$$

Where:

| Symbol | Meaning | Unit |
|---|---|---|
| $E$ | Energy | J |
| $P$ | Power | W |
| $t$ | Time | s |

Because:

$$
1J = 1W \cdot s
$$

---

## 6. Worked Example — Energy

A 100 W device operates for 10 seconds.

$$
E = Pt
$$

$$
E = 100 \times 10
$$

$$
\boxed{E = 1000J}
$$

The device transfers **1000 J** of energy during the 10-second
interval.

---

## 7. Power vs Energy

### Power

Power describes **how quickly energy is transferred**:

$$
P = VI
$$

Unit: **Watt (W)**

### Energy

Energy describes the **total amount of energy transferred**:

$$
E = Pt
$$

Unit: **Joule (J)**

### Key distinction

> **Power is a rate; energy is an amount.**

---

## 8. Power Electronics Example

Consider a buck converter with:

$$
V_{in}=60V
$$

$$
I_{in}=5A
$$

The input power is:

$$
P_{in}=V_{in}I_{in}
$$

$$
P_{in}=60\times5=300W
$$

Suppose the converter produces:

$$
V_{out}=24V
$$

$$
I_{out}=11.25A
$$

The output power is:

$$
P_{out}=V_{out}I_{out}
$$

$$
P_{out}=24\times11.25=270W
$$

### Power Loss

$$
P_{loss}=P_{in}-P_{out}
$$

$$
P_{loss}=300-270=30W
$$

### Efficiency

$$
\eta=\frac{P_{out}}{P_{in}}\times100\%
$$

$$
\eta=\frac{270}{300}\times100\%
$$

$$
\boxed{\eta=90\%}
$$

The 30 W difference represents power that is not delivered to the
output and is associated with losses in the converter.

---

## 9. Power Electronics Connection

Power and energy are fundamental to understanding:

- Converter input and output power
- Converter efficiency
- MOSFET conduction losses
- MOSFET switching losses
- GaN switching losses
- Inductor and capacitor losses
- PCB conduction losses
- Thermal design

A key relationship used later in power electronics is:

$$
P_{loss}=P_{in}-P_{out}
$$

and:

$$
\eta=\frac{P_{out}}{P_{in}}\times100\%
$$

These quantities will become especially important when analyzing
real buck and boost converters.

---

## Key Equations

### Electrical Power

$$
\boxed{P=VI}
$$

### Resistor Power

$$
\boxed{P=I^2R}
$$

$$
\boxed{P=\frac{V^2}{R}}
$$

### Electrical Energy

$$
\boxed{E=Pt}
$$

### Converter Efficiency

$$
\boxed{\eta=\frac{P_{out}}{P_{in}}\times100\%}
$$

---

## Key Takeaways

- Power describes the **rate of energy transfer**.
- Energy describes the **total amount of energy transferred**.
- Power is measured in watts.
- Energy is measured in joules.
- For a resistive load:

$$
P=VI=I^2R=\frac{V^2}{R}
$$

- Converter efficiency compares useful output power with input power.
- Power and energy are fundamental concepts in power electronics.