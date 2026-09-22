# 🌐 Week 2 — Day 1: IP Addresses

Today I continued my cybersecurity training by learning the fundamentals of IP addresses and IPv4.

## 📚 What I Learned

### 1. What is an IP Address?

An IP address is an address used to identify a device on a network and help data reach its correct destination.

Example:

`192.168.1.10`

Think of an IP address like an address for a device on a network.

---

### 2. What Does IP Mean?

IP stands for:

**Internet Protocol**

An **IP address** is an address used in networking.

---

### 3. IPv4

IPv4 is one version of the Internet Protocol used for addressing devices.

An IPv4 address has **4 octets** separated by dots.

Example:

`192.168.1.10`

It contains:

- 192 → 1st octet
- 168 → 2nd octet
- 1 → 3rd octet
- 10 → 4th octet

Each octet can have a value from **0 to 255**.

Example of a valid IPv4 address:

`8.8.8.8`

Example of an invalid IPv4 address:

`192.168.1.256`

because 256 is greater than 255.

---

## 🔒 Private IP Address

A private IP address is used to identify devices inside a local network such as a home, school, or office network.

Example:

`192.168.1.10`

### Private IPv4 ranges

- `10.0.0.0 – 10.255.255.255`
- `172.16.0.0 – 172.31.255.255`
- `192.168.0.0 – 192.168.255.255`

Examples:

- `192.168.1.10` → Private IP
- `172.20.5.10` → Private IP

A private IP address can change when it is dynamically assigned.

---

## 🌍 Public IP Address

A public IP address is used for a network's communication with the wider Internet.

For example, a home network may contain several devices:

```text
Laptop → 192.168.1.10
Phone  → 192.168.1.11
TV     → 192.168.1.12
