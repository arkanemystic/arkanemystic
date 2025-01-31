# 🚀 Devakh Rashie | Computer Science & Math

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/devrashie)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F)](https://www.instagram.com/devrashie/)

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract DevakhRashie {
    struct Education {
        string university;
        string[] majors;
    }
    
    struct Interest {
        string category;
        string[] details;
    }
    
    Education public education;
    mapping(uint256 => Interest) public interests;
    string[] public roles;
    
    constructor() {
        education = Education({
            university: "The Ohio State University",
            majors: ["Computer Science", "Mathematics"]
        });
        
        interests[0] = Interest({
            category: "tech",
            details: ["Blockchain", "AI", "Robotics"]
        });
        
        interests[1] = Interest({
            category: "music",
            details: ["Competitive A Cappella", "Performance"]
        });
        
        interests[2] = Interest({
            category: "learning",
            details: ["New Technologies", "Problem Solving"]
        });
        
        roles.push("Blockchain Research Assistant");
        roles.push("A Cappella Team Member");
    }
}
```

## 🤝 Let's Connect
Got an interesting project idea or research proposal? I'm always excited to collaborate on innovative solutions. Reach out through [LinkedIn](https://www.linkedin.com/in/devrashie) or follow my journey on [Instagram](https://www.instagram.com/devrashie/).

_"Building the decentralized future, one block at a time."_
