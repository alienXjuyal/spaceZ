     // In server.js (Node.js/Express)
     app.post('/api/save-idea', (req, res) => {
         // Authenticate user, then save idea ID to their profile in DB
         // e.g., using MongoDB: User.findByIdAndUpdate(userId, { $push: { savedIdeas: ideaId } })
         res.json({ message: 'Idea saved!' });
     });
     
